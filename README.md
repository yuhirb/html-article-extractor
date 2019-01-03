# html-article-extractor
A web page content extractor

# installation
```javascript
npm install html-article-extractor
```

# usage
```javascript
var htmlArticleExtractor = require("html-article-extractor");

var dom = new JSDOM("...");
var body = dom.window.document.body
result = htmlArticleExtractor(body);
console.log(result)
```