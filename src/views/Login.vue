<template>
  <div class="container">
        <h2>注 册</h2>
        <form>
            <div class="form-group">
                <label class="label" for="name">用户名：</label>
                <input type="text" class="form-control" id="name" placeholder="请输入用户名" />
            </div>
            <div class="form-group">
                <label class="label" for="password">密码</label>
                <input type="password" class="form-control" id="password" placeholder="请输入密码" />
            </div>
            <div class="form-group">
                <label class="label" for="email">Email</label>
                <input type="email" class="form-control" id="email" placeholder="请输入Email" />
            </div>
            <div class="form-group">
                <input class="form-checkbox" id="checkbox" type="checkbox" value="value" />
                <label class="labelb" for="checkbox">勾选登录</label>
            </div>
            <button type="button" class="btn">登录</button>
        </form>
    </div>
</template>

<style lang="scss" scoped>
body {
    position: relative;
    font-size: 13px;
    color: #505050;
    background: #fff;
    height:100%;
}
.container {
    width: 200px;
    margin: 0 auto;
}
h2 {
    text-align: center;
}
.form-control {
    width: 200px;
    height: 23px;
}
.form-group,
.btn {
    margin-top: 10px;
}
.form-group>.label {
    display: block;
}
.form-group>.form-control {
    border: 1px solid #bfc0c5;
}
.form-group>.form-control:hover {
    border: 1px solid #474d5b;
    color: #383e4b;
}
</style>
