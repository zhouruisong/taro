---
title: Taro.hideShareMenu(option)
sidebar_label: hideShareMenu
id: version-2.0.3-hideShareMenu
original_id: hideShareMenu
---

隐藏转发按钮

> [参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/share/wx.hideShareMenu.html)

## 类型

```tsx
(option?: Option) => Promise<CallbackResult>
```

## 参数

### Option

| 参数 | 类型 | 必填 | 说明 |
| --- | --- | :---: | --- |
| complete | `(res: CallbackResult) => void` | 否 | 接口调用结束的回调函数（调用成功、失败都会执行） |
| fail | `(res: CallbackResult) => void` | 否 | 接口调用失败的回调函数 |
| success | `(res: CallbackResult) => void` | 否 | 接口调用成功的回调函数 |

## 示例代码

```tsx
Taro.hideShareMenu()
```

## API 支持度

| API | 微信小程序 | H5 | React Native |
| :---: | :---: | :---: | :---: |
| Taro.hideShareMenu | ✔️ |  |  |
