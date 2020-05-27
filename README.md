# yann-chat
An instant chat server

## Quick start
- install redis
- install rabbitmq
- go get github.com/yann1989/yann-chat
- build the Yann-chat 
- edit the config
- start:  
- chat start --config config-path

## Usage
### connect
- ws://xx.xx.xx.xx:xx/websocket?authorization=xxxxxxxxxxxxxxxxxxxx
- The authorization is generated by your server. The Key.pem must same to your server.

# Future
- You can modify the storage history message module to start your business.
- You can integrate restful api to this project, such as history message, contact list, contact add...
