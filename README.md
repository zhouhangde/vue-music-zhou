# vue-music-zhou

> 音乐app

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


https://blog.csdn.net/sleepwalker_1992/article/details/82313821
使用vue-cli+webpack构建Vue项目，需要全局安装:
npm i webpack webpack-cli -g
npm install -g vue-cli
npm i -g eslint
npm i -g eslint-config-airbnb
npm i -g eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react
npm install cnpm -g --registry=https://registry.npm.taobao.org
npm install -g yarn
npm install 或yarn install

https://zhidao.baidu.com/question/502289895348209804.html
找不到命令：create-webpack
npm install webpack -g
npm uninstall -g vue-cli
npm install -g vue-cli

https://blog.csdn.net/fuyujiaof/article/details/83624503
npm uninstall vue-cli -g
npm install -g @vue/cli-init



C:\Program Files\Java\jdk1.8.0_91\bin;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;




C:\Program Files\Java\jdk1.8.0_91\bin;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;




npm
https://www.npmjs.cn/


npm的包安装分为本地安装（local）、全局安装（global）两种

本地安装:
npm install xxx 安装到命令行所在目录的node_module目录。
全局安装:
npm install xxx  -g 安装到 \AppData\Roaming\npm\node_modules目录。

https://blog.csdn.net/Baijinwen/article/details/77961746
修改node.js默认的npm安装目录  

默认C:\Users\Default\AppData\Roaming\npm\node_modules\node_modules

修改默认全局安装位置
npm config set prefix "D:\node-mk"
npm config set cache "D:\node-mk"
npm install -g cnpm --registry=https://registry.npm.taobao.org

npm config set registry https://registry.npm.taobao.org  -- 配置后可通过下面方式来验证是否成功

npm config get registry

查看npm配置
npm config ls

npm install -g @vue/cli

vue --version 或 vue -V 

查看npm的路径
npm config get prefix

https://blog.csdn.net/jianleking/article/details/79130667
https://www.cnblogs.com/menggirl23/p/9139444.html
设置node和npm的环境变量
%SystemRoot%\system32;%SystemRoot%;%SystemRoot%\System32\Wbem;%SYSTEMROOT%\System32\WindowsPowerShell\v1.0\;C:\ProgramData\chocolatey\bin;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Program Files\nodejs\

C:\Program Files\Java\jdk1.8.0_91\bin;C:\Program Files\nodejs;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;D:\node-mk

C:\Program Files\Java\jdk1.8.0_91\bin;C:\Program Files\nodejs;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;D:\node-mk;D:\node-mk\node_modules\vue-cli\bin
C:\Program Files\Java\jdk1.8.0_91\bin;C:\Program Files\nodejs;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;D:\node-mk
%SystemRoot%\system32;%SystemRoot%;%SystemRoot%\System32\Wbem;%SYSTEMROOT%\System32\WindowsPowerShell\v1.0\;C:\ProgramData\chocolatey\bin;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Program Files\nodejs\

C:\Program Files\Java\jdk1.8.0_91\bin;C:\Program Files\nodejs;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;D:\node-mk

C:\Program Files\Java\jdk1.8.0_91\bin;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler

C:\Program Files\Java\jdk1.8.0_91\bin;C:\Program Files\nodejs;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler;D:\node-mk

C:\Program Files\Java\jdk1.8.0_91\bin;C:\Program Files\nodejs;D:\Program Files (x86)\Microsoft VS Code\bin;C:\Users\Administrator\AppData\Local\Programs\Fiddler

目前node和npm都安装在系统变量中

vue -v失灵有可能是viscode没有重启

vue -V  --查看vue安装
webpack  -v  查看webpack

shift键失灵
https://jingyan.baidu.com/article/a501d80cf163d9ec630f5ef4.html


vue脚手架，vue-cli创建项目，可以初始化webpack项目，
1步骤
vue init webpack vue-music-zhou    （不要用npm  init webpack vue-music-zhou
目前出现控制台乱码问题?

vue-cli webpack vuedemo1

2 初始化选择第二种returntime-only可以减少6kb，但是需要以.vue开发，第一种则不需要以.vue开发
3安装vue-router--yes
4安装eslint语法检查（暂不安装，作者安装了
5使用starand标准
6后面都选择no
7选择使用npm去安装

8npm install安装依赖
9启动 npm run dev
10打包 npm run build



githup用户名密码
1728451471@qq.com
zh5235340133299


附加:
vue和webpack项目构建过程常用的npm命令
https://blog.csdn.net/github_39274378/article/details/77850225

webpack4安装与学习
https://www.cnblogs.com/cashin/p/8721979.html


从搭建vue-脚手架到掌握webpack配置（一.基础配置）
https://www.jianshu.com/p/f05269760d84






