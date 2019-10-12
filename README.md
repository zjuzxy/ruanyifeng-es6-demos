# ruanyifeng-es6-demos
阮一峰es6demos

## let 和 const 命令

1. 用```let``` ```cosnt```声明的变量**一定要在声明之后使用，否则就报错。**
1. [「每日一题」什么是立即执行函数？有什么作用？](https://zhuanlan.zhihu.com/p/22465092)
1. es6共有六种声明变量的方法。

## 解构赋值

1. 解构赋值用默认值的条件是对象的属性值**严格**等于```undefined```。


## 函数

1. 大括号被解释为代码块，所以如果箭头函数直接返回一个对象，必须在对象外面加上括号，否则会报错。

```js
// 报错
let getTempItem = id => { id: id, name: "Temp" };

// 不报错
let getTempItem = id => ({ id: id, name: "Temp" });
```
2. 箭头函数```this```