use catkin build rather than catkin_make  

```bash
# 编译整个工作空间
catkin build

# 只编译名为 my_package 的包
catkin build my_package
```

```bash
rqt_graph   ###to check ros nodes
```
launch is xml document,to open multiple modes at one file
```bash
<node... output="screen"/>   ### to show output in console,set the configution in  the launch file
```
