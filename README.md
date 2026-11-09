# sky-mini · WeChat Mini-Program (Sky Take-out)

> The customer-facing WeChat mini-program for the [sky-take-out](https://github.com/zhugela/sky-take-out) delivery system — browse dishes, build a cart, pay and track the order.

![WeChat](https://img.shields.io/badge/WeChat-Mini%20Program-07C160?logo=wechat&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)

---

## Pages

| Page | Purpose |
|---|---|
| `index` | shop home, category tabs, dish list with spec selection |
| `order` | cart and order confirmation |
| `pay` | payment hand-off |
| `success` | order result |
| `details` | dish detail and spec picker |
| `address` | address list and edit |
| `remark` | order notes |
| `my` | user centre, order history |
| `nonet` | offline state |

## Stack

Native WeChat mini-program (WXML / WXSS / JS), `wx.request` against the backend REST API, `common/` holds shared config and request helpers.

## Run

1. Open the project root in **WeChat DevTools**
2. Set your appid in `project.config.json`
3. Point the API base URL in `common/` at a running backend

## Note

Course project (recreated from the 苍穹外卖 curriculum) kept for practice and reference.
