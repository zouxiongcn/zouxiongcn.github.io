```
1、计算机——属性——高级系统设置
2、点击环境变量，系统变量 新建：
名称：JAVA_HOME
变量值：刚刚安装的路径（如：C:\Program Files\Java\jdk1.8.0_151）
3、系统变量CLASS_PATH
名称：CLASS_PATH
变量值：.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar
4、在系统环境变量中有一个path的环境变量，选中后选择编辑，
将JAVA_HOME添加进去即可，如图：在最后加上  %JAVA_HOME%\bin;
5、java -version
https://blog.csdn.net/gao_xu_520/article/details/78526621
```