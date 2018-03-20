# ys-class

[YS](https://github.com/yskit/ys-mutify) 架构之应用文件基础类，通用类。开发者可以通过继承该类来获得扩展能力。

# Install

```shell
npm i --save ys-class
```

# Usage

```javascript
const BaseClassModule = require('ys-class');

module.exports = class NewClassModule extends BaseClassModule {
  constructor(ctx) {
    super(ctx);
  }
}
```

> `ctx` 是一个请求通道聚合对象，一般指KOA等架构中的`context`对象，比如如下代码中的`ctx`

```javascript
app.use(async (ctx, next) => {
  // ctx ...
})
```

# License

It is [MIT licensed](https://opensource.org/licenses/MIT).