---
layout: post
title:  "Announcing Ionic 1.0 Beta!"
date:   "2014-03-18 08:00:00"
hide_date: true
categories: ionic
author: '<img src="http://www.gravatar.com/avatar/e130a4be9fba5eb5d932c813fbe3a58d?s=48&amp;d=mm" class="author-icon"><a href="http://twitter.com/maxlynch" target="_blank">@maxlynch</a>'
published: true
---

After much waiting, we are happy to announce the release of Ionic 1.0 Beta, as of today!

It's been a long time coming, with over 2000 commits made, 700 bugs fixed and closed, 20 animal-themed [alpha releases](https://github.com/driftyco/ionic/releases), and 34 awesome [contributors](https://github.com/driftyco/ionic/graphs/contributors) participating.

I like to look back at how far Ionic has come since we launched the alpha at the end of November 2013. "Launched" is probably the wrong word though, more like "exposed" by people really excited about we were doing, as we weren't at all ready yet!

But the Ionic team and all of the wonderful community contributors kicked ass and quickly found and fixed issues big and small, making Ionic ready for people to build some really [great apps](ionicframework.com/examples/showcase/).

With the beta update, you'll find a lot of great improvements, especially with documentation, but also some bigger changes to be aware of:

 * We've totally revamped the API docs for the more advanced directives and services in Ionic: http://ionicframework.com/docs/
 * The delegate system we used previously that let you interact with UI elements from your controllers (say, to scroll to the bottom of a scroll view) have been removed and replaced with a much more explicit system. Now, we expose in a well documented way a Controller for certain powerful UI elements that can be accessed directly on the scope.
 * We are moving towards a more declarative system for defining things like header buttons. That means instead of defining a scope variable in your controllers for `leftButtons`, you use a child directive `<ion-nav-buttons side="left">` which fits the Angular way a lot better.
 * We've added support for very customizable popup dialogs.

## What's next?

So, now that the beta is out, you might be wondering what's next for Ionic? It's pretty simple, actually. We will:

 * Obsess over performance. This is a constant thing for us.
 * Dramatically improve Android UI "fit" - making our UI fit into Android UI guidelines better.
 * Add support for Windows Phone 8.
 * Continue to fix issues and refine our testing process to reduce issues across devices.
 * Build out useful addons to the framework that enhance your mobile UIs

And that's just on the framework side. We are also working on a service layer to give your apps powerful backend functionality. While we aren't ready to release anything here yet, we are [hiring](/jobs) for great developers to help us build out the Ionic mobile platform.
