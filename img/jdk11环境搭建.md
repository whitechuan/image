# jdk11环境搭建

## jdk下载

Oracle官网：

​	https://www.oracle.com/java/technologies/javase-downloads.html

选择自己要下的jdk版本：

此次下载的jdk11

![image-20201113195051529](../../Images/jdk11环境搭建.assets/image-20201113195051529.png)

下载好后，进行解压，和环境配置

![image-20201113195534008](../../Images/jdk11环境搭建.assets/image-20201113195534008.png)

## jdk环境配置

### 	1.找到环境变量在哪？

![image-20201113195806584](../../Images/jdk11环境搭建.assets/image-20201113195806584.png)

​	点击后会弹出：

![image-20201113195921192](../../Images/jdk11环境搭建.assets/image-20201113195921192.png)

![image-20201113200013273](../../Images/jdk11环境搭建.assets/image-20201113200013273.png)

注：用户级环境变量与系统级环境变量的区别？



### 	2开始配置环境变量

 在系统变量中新建一个变量

![image-20201113200736104](../../Images/jdk11环境搭建.assets/image-20201113200736104.png)

找到系统变量path，进行编辑

![image-20201113200835483](../../Images/jdk11环境搭建.assets/image-20201113200835483.png)

将你刚配置的JAVA_HOME配置进path中

![image-20201113200941010](../../Images/jdk11环境搭建.assets/image-20201113200941010.png)

解释：

==为什么要单独建个JAVA_HOME呢？==

**因为：在你配置了JAVA_HOME以后可以很快的进行jdk版本的更迭，只需改你添加的变量，而不用去修改path变量，如果经常去修改，很容易就在path变量中修改错误，造成以前配的一些其他的环境变量也出想问题**

配置好后，点击确定退出

进入DOS命令窗口

![image-20201113201143027](../../Images/jdk11环境搭建.assets/image-20201113201143027.png)

在DOS命令界面键入: java后回车显著下图，这环境配置成功

![image-20201113201351734](../../Images/jdk11环境搭建.assets/image-20201113201351734.png)

查看一下jdk的版本：

![image-20201113201452907](../../Images/jdk11环境搭建.assets/image-20201113201452907.png)

也正确

自此jdk11环境变量配置成功

## 如何在idea中使用你配置好的jdk

首先打开idea，新建项目

​	![image-20201113202246836](../../Images/jdk11环境搭建.assets/image-20201113202246836.png)

选择jdk版本：

![image-20201113202442503](../../Images/jdk11环境搭建.assets/image-20201113202442503.png)

选着项目存放路径和名称

![image-20201113202713025](../../Images/jdk11环境搭建.assets/image-20201113202713025.png)

建议：

​	建议大家，在自己的除系统盘外的任意一个盘，或者自己做开发，就自己开一个盘专门用于开发用，里面分文件进行存放，想项目可以自己建一个文件夹来存放

![image-20201113202922436](../../Images/jdk11环境搭建.assets/image-20201113202922436.png)

注意:记得在自己的项目后添上项目名称，这样可以将项目存放进此文件夹内

![image-20201113203020497](../../Images/jdk11环境搭建.assets/image-20201113203020497.png)

示例：

![image-20201113203400823](../../Images/jdk11环境搭建.assets/image-20201113203400823.png)

若出现这个警告：

![image-20201113203447698](../../Images/jdk11环境搭建.assets/image-20201113203447698.png)

解决：在setting里面

![image-20201113203912628](../../Images/jdk11环境搭建.assets/image-20201113203912628.png)

![image-20201113203953882](../../Images/jdk11环境搭建.assets/image-20201113203953882.png)

