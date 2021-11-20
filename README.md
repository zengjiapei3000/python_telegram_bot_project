# python_telegram_bot_project
First time to use python-telegram-bot API, just in Python interactive command line. It's **not good** but can run!


## STEP:

 1. Typing `source botenv/bin/activate` to enter the venv. and before that I used to install python-telegram-bot using `pip install python-telegram-bot`.
 2. Using proxychains to run python was a method to resolve timeouterror, firstly configure the proxychains, the run
 `proxychains python` to enter the python interactive command line on proxy.
 3.Next typing this:  
 ```
 >>> import telegram`
 >>> bot = telegram.Bot(token='TOKEN')
 ```
 this TOKEN is from the botfather when you create your bot.
 Then check if your credentials are correct, call the [getMe](https://core.telegram.org/bots/api#getMe) API method:
```
>>> print(bot.get_me())
>>> {"first_name": "Toledo's Place Bot, "username": "ToledosPalaceBot"}
```
Successful when you looking like above code! If you don't using proxychains to run python interactive command line, maybe failed in there.