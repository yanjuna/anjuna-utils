# Anjuna Utils

A collecion of utilities and infrastructure provisioning scripts we use here and there.

## errno.py
Prints the name for a given errno value. For example
```
  $ ./errno 42 
  ENOMSG
```
Note: `sudo apt install moreutils` will give you an `errno` program that can translate
in both directions unlike the one above.
