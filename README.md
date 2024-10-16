# API utilizando C

## Compilação e Execução

#### 1 - Salve o código em um arquivo chamado api_server.c
#### 2 - Compile o código usando o GCC:
    gcc api_server.c -o api_server
#### 3 - Execute o servidor
    ./api_server

## Testando a API
    Você pode testar a API usando curl:
    curl http://localhost:8080
    Isso deve retornar uma resposta JSON com a mensagem "Hello, World!".

## Considerações
    - Este exemplo é bem básico e não inclui tratamento de erros robusto ou suporte a múltiplas requisições simultâneas.
    - Para aplicações mais complexas, considere usar bibliotecas como libmicrohttpd ou mongoose.

