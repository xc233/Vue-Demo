<style>
img{
    width: 60%;
    padding-left: 20%;
}
</style>

# 软件设计模式

## MVC
Model View Controller

## MVVM
Model-View-ViewModel

## 双向数据绑定
![](vue-binding.png)

# vue基础语法
* v-text / v-html
* v-if  / v-else
* v-show 比重新渲染快
* v-for(value,key,index) //键+值+索引
* sort
* computed 计算属性
* v-on
* v-model:双向数据绑定的特殊指令

JS数组操作：
* arr.splice()
一个值代表保留数组的长度，溢出的删除
两个值代表从第几个开始删，删除几个值

VueComponent：
* 因为Html不区分大小写，所以vue的js代码大写用[-小写字母]代替
* template
* props


vue computed 计算属性 和 methods 方法区别
* computed是有缓存的，只要绑定的响应式依赖不发生变化，每次调用它是不会重新进行计算的
* methods是没有缓存的，每次触发重新渲染的时候都会再次执行函数，如果数据量非常大的话，比较耗时间

Computed 
* getter(读值)
* setter(设值)

v-model 和 v-bind 的区别
* v-model 其实是 v-bind + v-click 的语法糖(Syntactic Sugar)，只适用于表单数据的双向绑定
* v-bind是可以动态修改value的值 (v-bind directive allow you to produce some dynamic value by typing some JS expression that in most cases depends on the data from data model )