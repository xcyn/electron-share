# electron

底座分享

## 目录结构 （双 package 方案）

- `build` electron 打包、签名、发布
- `assets` 资源文件
  - `images`
- `src` 源码目录
  - `main-process` Electron 主进程文件
  - `scss` css 相关
  - `js`
    - `common`
      - `apis` http 服务器接口
      - `sdks` sdk 适配器
    - 其余为渲染进程目录
  - `dist`
    - `app` Electron 的 app 目录
      - `main-process`
      - `js`
      - `css`
      - `assets`
      - `package.json`
    - `release` 发布的安装包
