wiki-test
=========

This is a **test repository for wikt**. It's supposed to be a wiki.

## Here is a fine title

And here is a fine paragraph. It can contain words in **bold** or *italic*.

Do you like code blocks:

```javascript
var yes = true;
```

Let's go to another article with a [link](article.md).

## Mardown support

With Markdown, you can write lists:

- this is a an item
- this is another item
- and this is a third item

You can write several levels of titles.

### Subtitle

This is inline code: `inline(code);` and this is a long code block:

```javascript
angular.module('wikt.filters', []).
    filter('interpolate', ['version', function (version) {
    return function (text) {
        return String(text).replace(/\%VERSION\%/mg, version);
    }
}]);
```
