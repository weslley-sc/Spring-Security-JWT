#### :dollar: Autenticação JWT com Spring Security.

<ol align="left">
<li><strong><a href="#--autor">Autor</a></strong></li>
 <li><strong><a href="#--sobre-o-projeto">Sobre</a></strong></li>
 <li><strong><a href="#--tecnologias">Tecnologias</a></strong></li>
 <li><strong><a href="#--aprendizados-back-end">Aprendizados Back-end</a></strong></li>
</ol>

🌎


### [](https://github.com/weslley-sc/Spring-Security-JWT#--sobre-o-projeto) 🔥 Sobre o projeto

Projeto desenvolvido durante o curso Spring-Security-JWT da <a src="https://web.dio.me">DIO.me</a>.

A aplicação consiste em criar usuários com autorização e ao fazer login é gerado um token de autenticação. Cada usuário tem suas permissões de qual rota poderá acessar. Essa permissão é definida na criação do usuário no "ROLE"
<br/>
=========================
Cadastro de usuário:
endpoiont: http://localhost:8080/users
```
{
	"name": "Gleydson",
	"username": "glysns",
	"password": "jwt123",
	"roles": [
		"USERS",
		"MANAGERS"
	]
}
```
<br/>
=========================
Login:
Endpoint:http://localhost:8080/login

```
{
	"username":"glysns",
	"password": "jwt123"
	
}
```



<br />




<br />

### [](https://github.com/weslley-sc/Spring-Security#--tecnologias) 🤖 Tecnologias

- **Java 17**
- **Spring Boot**
- **Hibernate JPA**
- **Spring Security**
- **JWT**
- **Banco H2**
- **Postman**
- **Intellij**

### [](https://github.com/weslley-sc/Spring-Security#--aprendizados-back-end) 🎉 Aprendizados Back-end

- Modelo de domínio
- Acesso a banco de dados
- Estruturar o back end no padrão camadas
  - Model
  - DTO
  - Services
  - Controllers
  - Repositories
  - Security
  - Config
- Criar endpoints da API REST

<br />

### [](https://github.com/weslley-sc/Spring-Security#--autor) 💎 Autor

<a >
 <img style="border-radius: 8px" src="https://avatars.githubusercontent.com/u/86158156?v=4" width="80px;" alt="Weslley Costa"/>
<br />
<sub><strong>Weslley Costa</strong></sub></a>

<br />
<br />

:point_down: Entre em contato.

<br />

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/weslley-da-silva-costa-b8569273/)](https://www.linkedin.com/in/weslley-da-silva-costa-b8569273/)
