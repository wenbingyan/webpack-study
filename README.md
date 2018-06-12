# webpack-study
webpack深入学习

## 1. 模块化
学习webpack之前，首先来了解一下 [模块化](https://github.com/wenbingyan/Blog/issues/3)的概念 

### 1.1 命名空间
开发网页要通过命名空间的方式来组织代码
- 命名空间冲突，两个库可能会使用同一个名称
- 无法合理的管理项目依赖和版本
- 无法方便的控制依赖的顺序

### 1.2 CommonJS
CommonJS 是一种广泛使用的`javascript`模块化规范，核心思想是通过`require`方法来同步地加载依赖的其他模块，通过moudle.exports到处需要暴漏的接口

<<<<<<< HEAD

### 封装一个webpack
