# MySQL_SyncPartial_MySQL

1、c.toml中的主从信息
2、修改 master.info 的日志节点信息
bin_name = "mysql.000010"
bin_pos = 2185
3、 nohup ./MySQL_SyncPartial_MySQL --config=./c.toml >> MySQL_SyncPartial_MySQL.log 2>&1 &
