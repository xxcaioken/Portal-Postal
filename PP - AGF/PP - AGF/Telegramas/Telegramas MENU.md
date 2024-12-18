- A área de [[telegrama]] serve para monitorarmos a situação de todos os telegramas que chegam para serem processados na [[AGF]].
- ![[Pasted image 20241216151702.png]]
- A primeiro momento o mais importante da tela são os [[Telegrama estados]].
- A segundo momento podemos falar das funcionalidades gerais:
	- Aonde o sistema de [[Telegrama]] pode ser pausado utilizando a própria interface do PP em:
		- ![[Pasted image 20241216153801.png]]
	- Serviço suspenso:
		- ![[Pasted image 20241216154203.png]]
	- Exportar todos os telegramas como json:
```
		- {
         "id":2017,
         "remetente":{
            "nome":"CLIENTE TESTE 51",
            "cep":"04203-002",
            "bairro":"IPIRANGA",
            "numero":"5300",
            "complemento":"",
            "endereco":"RUA BOM PASTOR"
         },
         "destinatario":{
            "nome":"HENRIQUE VELOSO",
            "cep":"88050-005",
            "bairro":"Cacupé",
            "numero":"4382.0",
            "complemento":"Final da rampa",
            "endereco":"Estrada Haroldo Soares Glavan"
         },
         "texto":"Sr(a) HENRIQUE VELOSO CPF 111.111.111-11\n\nA XX - EMPRESA, comunica que, na forma da Lei nº XX/97, incluído pela Lei XX/17, realizará no dia e hora 11.11.11, 11h, por meio de XXX, no endereço: https://www na forma e condições previstas no Edital 000.\n\nO evento será realizado na modalidade online, através do endereço eletrônico: https://www mencionado acima.\n\nEm caso de o Edital não for no 1º, será realizado o 2º no mesmo horário do primeiro.\n\nParticipando ou não, fica V.S.ª para exercer o seu direito de preferência na condição, sendo que deverá ser exercida até a data de realização do 2º. \n\nPara o exercício do direito, o valor atualizado deverá ser realizado em até 24h. Caso haja interesse em exercer este direito, entrar em contato o mais breve possível.\n\nDúvidas poderão ser consultadas pelo e-mail: x@x sob o título \"XX”, ou diretamente no site: https://www, ou pelo telefone: (00) 0000-0000. ",
         "adicionais":"",
         "copiaTelegrama":"",
         "pedidoConfirmacao":"",
         "valor":0.0,
         "etiqueta":"",
         "status":"PENDENTE"
      },{
         "id":2018,
         "remetente":{
            "nome":"CLIENTE TESTE 51",
            "cep":"04203-002",
            "bairro":"IPIRANGA",
            "numero":"5300",
            "complemento":"",
            "endereco":"RUA BOM PASTOR"
         },
         "destinatario":{
            "nome":"LEANDRO N MARTINS",
            "cep":"88050-005",
            "bairro":"Cacupé",
            "numero":"4382.0",
            "complemento":"Final da rampa",
            "endereco":"Estrada Haroldo Soares Glavan"
         },
         "texto":"Sr(a) LEANDRO N MARTIS CPF 111.111.111-11\n\nA XX - EMPRESA, comunica que, na forma da Lei nº XX/97, incluído pela Lei XX/17, realizará no dia e hora 11.11.11, 11h, por meio de XXX, no endereço: https://www na forma e condições previstas no Edital 000.\n\nO evento será realizado na modalidade online, através do endereço eletrônico: https://www mencionado acima.\n\nEm caso de o Edital não for no 1º, será realizado o 2º no mesmo horário do primeiro.\n\nParticipando ou não, fica V.S.ª para exercer o seu direito de preferência na condição, sendo que deverá ser exercida até a data de realização do 2º. \n\nPara o exercício do direito, o valor atualizado deverá ser realizado em até 24h. Caso haja interesse em exercer este direito, entrar em contato o mais breve possível.\n\nDúvidas poderão ser consultadas pelo e-mail: x@x sob o título \"XX”, ou diretamente no site: https://www, ou pelo telefone: (00) 0000-0000. ",
         "adicionais":"",
         "copiaTelegrama":"",
         "pedidoConfirmacao":"",
         "valor":0.0,
         "etiqueta":"",
         "status":"PENDENTE"
      }
```
- [[Formulário de telegrama]]:
	- ![[Pasted image 20241216154344.png]]
- Funcionalidades individuais:![[Pasted image 20241216155154.png]]
	- Marcar como enviado altera o [[Telegrama estados]]
	- Imprimir serve para imprimir o telegrama neste modelo:
		- ![[Pasted image 20241216155424.png]]
	- Imprimir serve para imprimir o telegrama neste modelo:
	- ![[ServTelegramaFormulario.pdf]]