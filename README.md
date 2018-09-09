# CMPE-273-Lab2
Lab 2 Assignment:
Create a calculator with function add(x, y) implemented using gRPC server and provide a client that calls the calculator server.

Included files:
-calculator.proto -calculator_client.py -calculator_server.py

How to Run:
Generate calculator_pb2 and calculator_pb2_grpc files

python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. ./calculator.proto
Run Server

python calculator_server.py
Run Client (In a Separate Tab)

python calculator_client.py

Add Request is done with x= 3.00 and y = 2.00
Greeter client received: 5.00
