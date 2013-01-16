# Fine Uploader 3.2 for Rails

[Fineuploader](http://fineuploader.com/) is a Javascript plugin written by [Andrew Valums](http://github.com/valums/), and actively developed by [Ray Nicholus](http://lnkd.in/Nkhx2C). This plugin uses an XMLHttpRequest (AJAX) for uploading multiple files with a progress-bar in FF3.6+, Safari4+, Chrome and falls back to hidden-iframe-based upload in other browsers (namely IE), providing good user experience everywhere. It does not use Flash, jQuery, or any external libraries.

This gem integrates this fantastic plugin with Rails 3.1+ Asset Pipeline.

[Plugin documentation](https://github.com/valums/file-uploader/blob/master/readme.md)

## Installing Gem

    gem 'fine-uploader-rails', '~> 3.2'

## Using the javascripts

Require fineuploader in your app/assets/application.js file

    //= require fineuploader

Fineuploader with JQuery wrapper

    //= require fineuploader.jquery

## Using the stylesheet

Require the stylesheet file to app/assets/stylesheets/application.css

    *= require fineuploader

## Thanks
Thanks to [Andrew Valums](http://github.com/valums/) and [Ray Nicholus](http://lnkd.in/Nkhx2C) for this plugin.