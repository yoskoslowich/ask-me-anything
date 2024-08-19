## Ask Me Anything (AMA)

Uma aplicação “Ask Me Anything” (AMA) é uma plataforma ou funcionalidade que permite aos usuários fazerem perguntas sobre qualquer assunto a uma pessoa ou entidade específica. Esse conceito é bastante popular em redes sociais e fóruns, como o Reddit, onde pessoas de diferentes áreas de expertise, celebridades, ou figuras públicas se disponibilizam para responder perguntas dos usuários.

#### Dependências

```
go install github.com/jackc/tern/v2@latest
go mod tidy
```

#### Para subir a aplicação
```
docker-compose up -d
go run cmd/ama/main.go
```
