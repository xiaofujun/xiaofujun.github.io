# 前后端的默认数据约定

## switch 开关

1. 前端调用接口传值时`开启传值 '1'`, `关闭传值 '0'`
2. 后端返回数据时，开启值为 '1' 或者 1，关闭值为 '0' 或者 0 （推荐统一返回字符串的 '1' 和 '0'）

## form 的联动隐现

返回数据中在 `items` 指定项添加 `otherParams.showWhere` 字段 实现。具体格式参考 [校验规则](validator.md)