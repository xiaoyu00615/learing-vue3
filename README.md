# vur3_Learing

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

# 创建  / 初始化仓库 - bash
$ 新建一个文件夹
mkdir my-project
cd my-project


$ 初始化后 会在当前目录生成  .git 隐藏文件夹 （仓库核心文件） - 本地仓库
git init


$ 在当前文件夹中添加文件 - 工作区
index.html
style.css
script.js


$ 添加文件夹所有修改 工作区的代码  工作区 -> 暂存区
git add .


$ 暂存区 -> 本地仓库
git commit -m '描述'


$ 连接远程仓库 进行关联 后面的远程仓库是我的记得修改 - 建议使用 SSH
git remote add origin 填写远程仓库
如：git@github.com:xiaoyu00615/vue-practice.git


$ 本地仓库推送到远程仓库  本地仓库  -> 远程仓库
git push -u origin main




// 查看现在的远程仓库
git remote -v


// 查看分支
git branch


// 创建分支
git branch feature-login


常见分支
main/master -- 主分支

develop -- 开发分支

feature -- 功能分支

hotfix -- 修复分支

