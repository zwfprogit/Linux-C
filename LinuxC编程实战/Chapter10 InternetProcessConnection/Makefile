all:
	gcc -o pipe pipe.c
	gcc -o dual_pipe dual_pipe.c
	gcc -o procread procread.c
	gcc -o procwrite procwrite.c
	gcc -o ftok ftok.c
	gcc -o sendmsg sendmsg.c
	gcc -o rcvmsg rcvmsg.c
	gcc -o opmsg opmsg.c
	gcc -o server server.c
	gcc -o client client.c
	gcc -o writer -I./ writer.c
	gcc -o reader -I./ reader.c


clean:
	rm -rf pipe dual_pipe procread procwrite ftok sendmsg rcvmsg opmsg server client writer reader

