# 🌡️ Monitor de Temperatura e Luminosidade

Sistema com Arduino para monitoramento de temperatura e luminosidade em tempo real, com sinalização visual e sonora.

## 🚀 Funcionalidades

* Leitura de temperatura com LM35
* Leitura de luminosidade com LDR
* LEDs indicam níveis de temperatura e luz
* Buzzer para alerta de alta temperatura
* Média de leituras para maior precisão

## 🔧 Componentes

* Arduino Uno
* LM35 (sensor de temperatura)
* LDR (sensor de luz)
* LEDs
* Buzzer
* Resistores
* Protoboard

## ⚡ Ligações

* LM35 → A1
* LDR → A0
* LEDs → pinos 5 ao 10
* Buzzer → pino 2

## 🧠 Lógica

* Temperatura ativa LEDs por faixa (10°C, 20°C, 30°C)
* Luminosidade controla LEDs por intensidade
* Buzzer dispara em temperatura alta

## 👨‍💻 Autor

**Willys Tecnologia IoT**
