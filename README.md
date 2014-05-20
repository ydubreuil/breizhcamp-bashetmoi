# Slides of my Bash presentation at BreizhCamp 2014

Based on the Google IO 2013 template. See here: https://code.google.com/p/io-2013-slides/

## Running the slides

The slides can be run locally from `file://` making development easy :)

### Running from a web server

If at some point you should need a web server, use [`serve.sh`](serve.sh). It will
launch a simple one and point your default browser to [`http://localhost:8000/template.html`](http://localhost:8000/template.html):

    $ cd io-2012-slides
    $ ./serve.sh

You can also specify a custom port:

    $ ./serve.sh 8080

### Presenter mode

The slides contain a presenter mode feature (beta) to view + control the slides
from a popup window.

To enable presenter mode, add `presentme=true` to the URL: [http://localhost:8000/template.html?presentme=true](http://localhost:8000/template.html?presentme=true)

To disable presenter mode, hit [http://localhost:8000/template.html?presentme=false](http://localhost:8000/template.html?presentme=false)

Presenter mode is sticky, so refreshing the page will persist your settings.

## Sources for this presentation

* http://www.ukuug.org/events/linux2003/papers/bash_tips/ : Power Shell Usage: Bash Tips &amp; Tricks - UKUUG
* https://docs.google.com/presentation/d/1W1plgpZ4S9qgvt-5MWyAbty26uHpu-K-Fe5qfM61u3I : Introduction to Bash Scripting LFNW 2013
