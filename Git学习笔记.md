### Git学习笔记

**git**：分布式版本控制系统。

**repository**：版本库、仓库，可以简单理解成一个目录，这个目录里面的所有文件都可以被Git管理起来，每个文件的修改、删除，Git都能跟踪，以便任何时刻都可以追踪历史，或者在将来某个时刻可以“还原”。

初始化仓库：

```
git init
```

添加文件到仓库：

```
git add
git commit -m "messege"
```

查看仓库当前的状态、查看修改的内容

```
git status
git diff
```

版本回退（当前版本号为HEAD，上个版本号为HEAD^，以此类推。或者使用`git reflog`查看）

```
git reset --hard ...
```

查看提交历史记录

```
git log
```

查看命令历史记录

```
git reflog
```

撤销工作区的修改

```
git checkout -- file
```

tttt