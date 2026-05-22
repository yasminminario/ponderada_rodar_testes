# Ponderada Testes

## Nome: Yasmin MInário
## Turma: T13

<img width="1257" height="214" alt="image" src="https://github.com/user-attachments/assets/2b712b1c-59ad-4ada-8c9e-c5e3acf967ba" />

&emsp;Os testes em ```TestesConversorTemperatura.cs``` verificam que o método ```ConversorTemperatura.FahrenheitParaCelsius``` converte corretamente vários valores de Fahrenheit para Celsius (ex.: 32→0, 212→100 e casos com decimais), comparando o resultado esperado com o calculado.

https://github.com/yasminminario/DotNet5-xUnit



<img width="1366" height="366" alt="image" src="https://github.com/user-attachments/assets/da8a0b79-64a3-4252-9d19-c44b2a7ad068" />

&emsp;Os testes em ```TestesAnaliseCredito.cs``` usam ```Moq``` e ```FluentAssertions``` para validar ```AnaliseCredito.ConsultarSituacaoCPF``` com um ```IServicoConsultaCredito``` simulado, cobrindo quatro cenários: CPF inválido (```ParametroEnvioInvalido```), erro de comunicação (```ErroComunicacao```), CPF sem pendências (```SemPendencias```) e CPF com pendência (```Inadimplente```).

https://github.com/yasminminario/DotNet5-Moq-xUnit-FluentAssertions



<img width="1377" height="658" alt="image" src="https://github.com/user-attachments/assets/93b51528-13ea-42fc-9176-d799dd4f2eb8" />

&emsp;Esses testes validam a simulação de juros compostos da API, conferindo se, para diferentes combinações de valor do empréstimo, prazo em meses e taxa mensal, o cálculo retorna o valor final esperado. Em resumo, eles garantem que a fórmula de juros compostos está funcionando corretamente e produzindo o total a pagar dentro do cenário de negócio definido.


https://github.com/yasminminario/ASPNETCore5-REST_API-xUnit-SpecFlow-Swagger-Docker_JurosCompostos
