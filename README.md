# New Map

###### A web app that combines data or functionality from multiple sources. You need to combine data from Google News with functionality from Google Maps!

**With the help of**:

* Google Maps offers an API that allows you to embed Google’s maps into your own web apps. wow, fantastic!
Where to read about Google Maps Javascript API ? [here](https://developers.google.com/maps/documentation/javascript/)

* Google News parameters: [this guide](http://i-tweak.blogspot.com/2013/10/google-news-search-parameters-missing.html)

The idea is to create a bulleted list of articles' titles and links.

How to get those without "scraping" this page’s HTML?  -- RSS -- a flavor of XML (a tag-based markup language)
RSS allows to do so, because it is "machine-readable" (it adheres to a standard format, we can parse it with software).
Where to read about RSS? [here](https://cyber.law.harvard.edu/rss/rss.html)

[jQuery’s documentation](http://learn.jquery.com/)

**index.html**
* body, inside of which is div with a unique id of map-canvas. It’s into that div that a map is injected. Below that  div is a form, inside of which is an input of type text with a unique id of q that is used to take input from users.

**styles.css**
* UI
    
**scripts.js**
* implementation of "front-end" UI, relying on Google Maps and some "back-end" Flask routes for data.
    
**helpers.py**
* queries Google News for articles for a particular geography, falling back on The Onion if none are available.









