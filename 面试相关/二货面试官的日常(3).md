# 二货面试官日常(3)

**大嘴面试官:**<br />年底了，好多公司都在搞年会，我在git上发现一个比较有意思的东西。<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/313624/1578270422838-bc2f5066-8344-485b-bbfa-3c1b34bebcea.png#align=left&display=inline&height=285&name=image.png&originHeight=1050&originWidth=1794&size=424113&status=done&style=none&width=487)<br />**老白：**<br />咱部门啥时候年会？<br />**大嘴面试官:**<br />有么？<br />**老白：**<br />![682346bce3fd9a918a53124d92f2c2e1.gif](https://cdn.nlark.com/yuque/0/2020/gif/313624/1578270635891-5dbfe15a-c2ee-4660-9929-b0a8cfa14ceb.gif#align=left&display=inline&height=174&name=682346bce3fd9a918a53124d92f2c2e1.gif&originHeight=253&originWidth=450&size=21224&status=done&style=none&width=306)<br />那你最近面试有没有遇到什么好玩的事情？<br />**大嘴：**<br />发现一个比较火的笔试或面试题，那个题目已经被讨论好久了，网上也有一大推解析说明。<br /><<前端程序员经常忽视的一个JavaScript面试题>><br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/313624/1578270895346-e8c281bc-9c22-414a-8a92-c15ac09ad0ca.png#align=left&display=inline&height=305&name=image.png&originHeight=610&originWidth=664&size=630087&status=done&style=none&width=332)<br />有兴趣可以去了解一下？<br />**老白：**<br />再见~<br />**大嘴：**<br />里面大部分考察的都是js的基础知识

- 对象的基本概念：**调用公有方法，公有属性，必需先实例化对象；** **静态方法和静态属性就是无需实例化可以调用**；
- **JavaScript 解释器中存在一种变量声明被提升的机制，也就是说函数声明会被提升到作用域的最前面，即使写代码的时候是写在最后面，也还是会被提升至最前面。**
- **而用函数表达式创建的函数是在运行时进行赋值，且要等到表达式赋值完成后才能调用**
> Javascript中**函数声明**和**函数表达式**是存在区别的，**函数声明**在JS**解析时**进行函数提升，因此在同一个作用域内，不管函数声明在哪里定义，该函数都可以进行调用。而**函数表达式**的值是在JS**运行时**确定，并且在表达式赋值完成后，该函数才能调用。

- JS没有块级作用域，但是函数是能产生一个作用域的，函数内部不同定义值的方法会直接或者间接影响到全局或者局部变量，函数内部的私有变量可以用闭包获取
- this的指向在函数定义的时候是确定不了的，只有函数执行的时候才能确定this到底指向谁，实际上this的最终指向的是那个调用它的对象
- JS的运算符优先级问题, 建议参考，

[https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Operators/Operator_Precedence](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)<br />大部分内容都是摘自github：<br />[https://github.com/Wscats/articles/issues/85](https://github.com/Wscats/articles/issues/85)<br />**老白：**<br /> **new new Foo().getName()** 现实中会有人这么写么？ 有人会遇到这样的队友？<br />**大嘴：**<br />面试题目而已，主要是为了考查一些基础，不过这些题目觉得作为校招题目挺好，社招的话意义不大。

![image.png](https://cdn.nlark.com/yuque/0/2020/png/313624/1578272374858-26a8730e-55b6-4951-82c7-5da161e1d8f6.png#align=left&display=inline&height=138&name=image.png&originHeight=275&originWidth=406&size=78659&status=done&style=none&width=203)
