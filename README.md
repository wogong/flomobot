# flomo bot

使用 Telegram 机器人发送笔记到你的 Flomo. 你需要有一台可访问 Telegram 服务器的服务器(主机/VPS)。

## Steps

1. @BotFather 新建机器人，获取 token
2. Flomo 官网获取 API，链接 <https://flomoapp.com/mine?source=incoming_webhook>
3. `cp config-example.py config.py`, 修改对应字段为前两步获取的值
4. 安装依赖 `pip install -r requirements.txt`
5. `python floambot.py`

## Usage

给新建的机器人发送消息，回复内容 `200 OK` 表明添加笔记到 Flomo 成功，可去官网检查。

PS:

[Flomo]((https://flomoapp.com/)) 是一个崇尚无压输入的笔记工具，欢迎使用我的邀请链接注册 <https://flomoapp.com/register2/?Njg4NQ>