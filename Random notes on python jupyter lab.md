
When using a new browser or switching to a new place to open jupyter notebook, often need to enter the url and token.
Go to the previous jupyter lab browser window that worked, open terminal (under Launcher -> other)
Can also just do this in the terminal like Windows PowerShell

use the command
```
jupyter server list
```

and you will get the token (marked out between )
```
Currently running servers:
http://localhost:8888/?token=🐦some_number_and_alphabet_combination🐦 :: path_and_filename(ex: C:\user...)
```