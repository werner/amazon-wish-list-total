amazon-wish-list-total
=====================

A Google Chrome extension that totals up the price of all items in the current
Amazon wish list, and displays it unobtrusively below the wish list title.

![Screenshot](https://raw.githubusercontent.com/jasontbradshaw/amazon-wish-list-total/master/screenshots/screenshot-1.png)

Description
----
Ever get tired of having to manually total up the items in your wish list, click
a button to figure out how much it all costs, or add all the items to the cart
to get that one magic number?

Worry no more! This extension adds an unobtrusive total price below the wish
list title, and updates it dynamically when items are added or deleted.

It supports both the "normal" and "compact" views for wish lists, and skips
totaling items that aren't currently available. It should also support multiple
currencies (it uses
[accounting.js](http://openexchangerates.github.io/accounting.js/) to parse the
prices), but this is untested.

Limitations
----
With enough demand, these could be implemented in the future, but here's what
the extension _doesn't_ do:

* Gives a total only for the current page of results
* Doesn't include items that aren't currently available on Amazon.com
