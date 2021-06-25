# Qutebrowser Dark Dracula

This is a fork of the [Dark solarized](http://ethanschoonover.com/solarized) css stylesheet for the [qutebrowser](https://qutebrowser.org). This is the same thing but themed towards the [Dracula](https://draculatheme.com) instead.


## Screenshots

![Google](screenshots/sol-google.png)
![StackOverflow](screenshots/sol-stack.png)
![Git](screenshots/sol-git.png)
![HackerNews](screenshots/sol-hn.png)
![Medium](screenshots/sol-medium.png)
![WikiArch](screenshots/sol-arch.png)
![Wikipedia](screenshots/sol-wik.png)

## Style

There are two stylesheets :
- *dracula-dark.css* 
- *custom_dracula.css* 


## Usage

### In settings

Tape `:set` and put their names in `content.user_stylesheets` with your path.

Example :

```
["dracula-dark.css", "custom_dracula.css"]

```

### In config

In `config.py` :

```
c.content.user_stylesheets = [
    'dracula-dark.css',
    'custom_dracula.css'
]
```

## Sites I tested

- https://www.google.com
- https://en.wikipedia.org
- https://wiki.archlinux.org
- https://docs.python.org
- https://github.com/
- https://stackoverflow.com
- https://stripe.com/docs
- https://docs.adyen.com
- http://flask.pocoo.org/docs
-  https://news.ycombinator.com/
- https://medium.com
...

## TODO

Improve the style when displays code (ex comments in git)



