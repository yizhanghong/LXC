# 尝试统一LEDE/ImmortalWrt/OpenWRT Official X86三个版本的config文件 ing ...

## LEDE/ImmortalWrt/OpenWRT Official X86_X64 mini（主力更新）
> [!TIP]
> **插件：基础功能、IPV6、Wireguard、SSR Plus+、PW、OC、Argon 主题、AdGuard Home、Mosdns、upnp、ShutDown/关机、SmartDNS**

>  **待加入：mosdns（貌似现在不支持LEDE了，https://github.com/sbwml/luci-app-mosdns/issues/252#issuecomment-2336829767 ）**

>  **待完成：统一LEDE/ImmortalWrt/OpenWRT Official mini配置文件，但是很懒。PS：只能怪LXC真的太省心，部署完基本不需要维护**

> ~~待解决，直接使用管理界面无法打开，需更改uhttpd注释掉 443 相关的两行。 https://github.com/coolsnowwolf/lede/issues/11546 ！~~
> > **2024.11.15貌似修复了此问题，采用替换uhttpd配置文件的方式，貌似顺便修复了网口的问题,测试一下。目前只编译了X86_X64版**


## 感谢

**[xYx-c/build-openwrt](https://github.com/xYx-c/build-openwrt) 、[Zane-E/ROOTFS](https://github.com/Zane-E/ROOTFS) 、[217heidai/OpenWrt-Builder](https://github.com/217heidai/OpenWrt-Builder) 、[db-one/OpenWrt-AutoBuild](https://github.com/db-one/OpenWrt-AutoBuild) 、[shidahuilang/openwrt](https://github.com/shidahuilang/openwrt) 、[haiibo/OpenWrt](https://github.com/haiibo/OpenWrt) 、[ophub/amlogic-s9xxx-openwrt](https://github.com/ophub/amlogic-s9xxx-openwrt) 等等无私的大神分享及教程**

## 鸣谢

- 感谢[openwrt源码](https://github.com/openwrt/openwrt) 、[LEDE源码](https://github.com/coolsnowwolf/lede) 、[ImmortalWrt源码](https://github.com/immortalwrt/immortalwrt)
- 感谢[@P3TERX](https://github.com/P3TERX),[P3TERX大佬的云编译](https://github.com/P3TERX/Actions-OpenWrt)



## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [Zane-E/ROOTFS](https://github.com/Zane-E/ROOTFS)
- [https://github.com/haiibo/OpenWrt](https://github.com/haiibo/OpenWrt)
- [https://github.com/xYx-c/build-openwrt](https://github.com/xYx-c/build-openwrt)
## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)

