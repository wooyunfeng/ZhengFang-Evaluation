

# ZF-Evaluation

正方教务管理系统-批量自动评价教学质量评价功能

<a href="javascript: (function() {var script = document.createElement('script');script.type = 'text/javascript';script.src = 'https://rawgit.com/ZengGUI/ZF-Evaluation/master/script.js';document.getElementsByTagName('head')[0].appendChild(script);})()"><button type="button" onclick="alert('你需要把我拖拽到书签栏里面喔！')">教学一键评价</button></a>

### 使用方法1：

* PS：浏览器推荐使用 Chrome， Safari， Firefox 等
* 把上面的**教学一键评价**按钮拖到书签栏
* 登录教务管理系统，点击进入教学质量评价，选中**第一门**需要评价的课程
* 在评价页面点击书签栏的你刚才拖拽的按钮，就会自动完成所有评价
* 等待一会儿会提示你**评价完成** ，然后点一下**提交** 就好啦



### 使用方法2：

* 登录教务管理系统，点击进入教学质量评价，选中**第一门**需要评价的课程
* 在浏览器中按 **F12**打开，然后切换到控制台(Console) 
* 复制下面的js代码

```javascript
var script = document.createElement("script");
script.type = "text/javascript";
script.src = 'https://rawgit.com/wooyunfeng/ZhengFang-Evaluation/master/script.js';
document.getElementsByTagName("head")[0].appendChild(script);
```
* 粘贴到控制台，回车运行 ，就会自动完成所有评价，提示**评价完成**，点**提交**就可以了

  ​

