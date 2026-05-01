# PATCH NOTES

## 1.1.6 (29/04/2026)
- [FIX]: reversão do ads-banner para tamanho fixo (adaptativo causava corte e layout shift)

## 1.1.5 (29/04/2026)
- [FIX]: sizedbox do ads-banner considera os dois sentidos
- [FIX]: bloqueio de orientação para retrato
- [BUG]: ads-banner continua cortado na horizontal

## 1.1.4 (29/04/2026)
- [FIX]: box protegendo espaço para o ads-banner, evitando que a tela pule e corte o ads-banner
- [BUG]: ads-banner cortando na horizontal
- [BUG]: ao girar a tela do celular quebra tudo

## 1.1.3 (29/04/2026)
- [FEATURE]: mudança no ads-banner para ser adaptativo
- [FIX]: versão do SDK fixada em 36 (o Google Console mostrava incompatibilidade se deixasse livre)
- [BUG]: ads-banner aparece cortado e demora um pouco para dar load, fazendo a tela pular

## 1.1.2 (27/04/2026)
- [FIX]: boolean do tutorial visto muda no início do tutorial, tanto faz se é pelo iniciar missão ou pelo ver tutorial
- [FIX]: ranking deixa claro que só conta vitórias
- Versão estável (sem bugs detectados)

## 1.1.1 (27/04/2026)
- [FIX]: a linha de embaralhar o deck estava comentada (esqueci em algum debug de voltar ao normal)
- [BUG]: tutorial aparecendo duas vezes quando clica primeiro no tutorial e depois em missão
- [BUG]: ranking não atualiza quando ocorre derrota

## 1.1.0 (27/04/2026)
- [FEATURE]: ranking individual
- [FEATURE]: níveis de dificuldade nas missões
- [BUG]: baralho sempre na mesma ordem

## 1.0.2 (20/04/2026)
- [FIX]: atualização dos textos do tutorial
- [FEATURE]: melhorias de interface: remoção de alguns textos/avisos redundantes e borda curva nas cartas
- Versão estável (sem bugs detectados)

## 1.0.1 (16/04/2026)
- [FIX]: mudança de configuração no build.gradle
- [BUG]: textos em inglês do tutorial faziam referência a versão antiga

## 1.0.0 (16/04/2026)
- [BUG]: instalou mas não abria o app no celular

# TO DO LIST

## 1.2
- achievements
- bônus permanentes ativáveis relacionados a cada achievement
- analytics
- ad adaptativa

## 1.3
- ranking global

## 2.0
- modo aventura
