原型、原型链

#### 1、定义：实例对象、实例函数、实例函数的原型
* 实例对象由实例函数生成
* 实例函数可通过prototype操作实例函数的原型
* 实例对象的__proto__指向实例函数的原型，及实例对象继承实例函数原型的属性
* 实例函数的prototype等于实例函数原型
* 函数原型的constructor等于函数实例


#### 2、js底层定义
* 所有函数的__proto__指向js函数原型
* js函数原型__proto__指向obj的原型
* obj的原型指向null(防止循环，需要一个终点)