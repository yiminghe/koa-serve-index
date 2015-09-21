# koa-serve-index

koa version of express serve index middleware

https://github.com/expressjs/serve-index

[![koa-serve-index](https://nodei.co/npm/koa-serve-index.png)](https://npmjs.org/package/koa-serve-index)
[![NPM downloads](http://img.shields.io/npm/dm/koa-serve-index.svg)](https://npmjs.org/package/koa-serve-index)
[![Build Status](https://secure.travis-ci.org/yiminghe/koa-serve-index.png?branch=master)](https://travis-ci.org/yiminghe/koa-serve-index)
[![Coverage Status](https://img.shields.io/coveralls/yiminghe/koa-serve-index.svg)](https://coveralls.io/r/yiminghe/koa-serve-index?branch=master)
[![Dependency Status](https://gemnasium.com/yiminghe/koa-serve-index.png)](https://gemnasium.com/yiminghe/koa-serve-index)
[![node version](https://img.shields.io/badge/node.js-%3E=_0.11-green.svg?style=flat-square)](http://nodejs.org/download/)


## difference between expressjs/serve-index

- support fileSort option: [#3](https://github.com/yiminghe/koa-serve-index/pull/3)


## example

```javascript
var app = require('koa')();
app.use(require('koa-serve-index')(process.cwd()));
app.listen(90);
```