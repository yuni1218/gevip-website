# GEVIP website (v2, work in progress)

A rebuild of the Galaxy Evolution VIP site (https://sites.utexas.edu/vip/).

No build tools required — it's plain HTML, CSS, and JS. Open `index.html`
in a browser to preview it, or use a local server (see below).

## Structure

```
index.html       # all page content
css/style.css    # all styling
js/main.js       # mobile nav toggle
images/          # put photos/logos here, then reference as images/filename.jpg
```

## What's placeholder right now

Search the code for `PLACEHOLDER` to find everything that needs real
content: project cards, staff photos/names, FAQ answers, and a couple
of "link to a page that doesn't exist yet" spots.

## Previewing locally

Any of these work:

- Just double-click `index.html` to open it in a browser.
- Or, from this folder, run a tiny local server so relative paths
  behave exactly like they will on the live site:
  ```
  python3 -m http.server 8000
  ```
  then visit http://localhost:8000

## Deploying

This is set up to be hosted with GitHub Pages directly from this repo
(see the main setup instructions for how to turn that on).
