# b2b-view
1、git clone https://github.com/yonghuisd/b2b-view.git

2、安装node 5.10版本.

3、全局安装webpack

4、打开cmd,切换到代码根目录

5、运行npm install 

6、运行npm run dev, 报错没关系，是报的格式错误。

7、运行npm run start,服务启动在8080端口

8、http://localhost:8080/ 支持字符串及json输出

9、http://localhost:8080/test 模板引擎输出

10、http://localhost:8080/ssr   React 服务器渲染

11、http://localhost:8080/page   React SSR 前后端同构渲染

12、本次版本所包含的特性:

      a、前端工程化
   
      b、资源模块化，包括js模块化、css模块化、图片、字体等模块化

      c、SSR  react 服务器端渲染

      d、React isomorphic 前后端同构渲染

13、可以在routes/pages中添加路由自行测试。

14、在src中添加react模块，添加打包入口，使用npm run build 打包，添加模块或路由需要重启服务：npm run start
