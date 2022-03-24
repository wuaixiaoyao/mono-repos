# monorepo UI Lib

## lerna

#### 常用命令

> [lerna 工作流使用指南](https://zhuanlan.zhihu.com/p/404166248)

```bash
    # 添加依赖到指定package
    lerna add  @wuaixiaoyao-lib/button --scope @wuaixiaoyao-lib/form
    # 发布
    lerna publish  
```

### npm 私有仓库

- `verdaccio` 搭建
- npm 仓库 组织 e.g. @@wuaixiaoyao-lib

### 参考

- [lerna 搭建脚手架](https://segmentfault.com/a/1190000040277957#item-4-14)

- [使用Lerna & Yarn Workspaces 构建mono-repo项目](https://www.zhihu.com/search?hybrid_search_extra=%7B%22sourceType%22:%22article%22,%22sourceId%22:70782864%7D&hybrid_search_source=Entity&q=yarn%20workspace&search_source=Entity&type=content)
- [monorepo](https://www.zhihu.com/search?hybrid_search_extra=%7B%22sourceType%22:%22article%22,%22sourceId%22:70782864%7D&hybrid_search_source=Entity&q=yarn%20workspace&search_source=Entity&type=content)
- [请问有人使用monorepo的模式来管理代码库吗？体验怎么样？](https://www.zhihu.com/question/318476028/answer/1895685159)
