

# 🇧🇷 Português

## Sobre o projeto

O **Instance Tracker** é um plugin para Roblox Studio desenvolvido para ajudar programadores a inspecionar, monitorar e compreender a hierarquia de Instances de seus jogos através de uma interface centralizada.

O projeto oferece ferramentas para exploração de hierarquia, monitoramento de eventos, pesquisa global e inspeção de memória.

## Funcionalidades

### General
- Visão geral das Instances monitoradas.
- Monitoramento de atividades.
- Acesso rápido a informações importantes.

### Explorer
- Exploração da hierarquia de Instances.
- Inspeção de objetos e suas estruturas.
- Monitoramento de alterações na hierarquia.

### Event Logs
- Sistema centralizado de logs.
- Registro de adição e remoção de Instances.
- Visualização das atividades através da interface.

### Search
- Pesquisa global de Instances.
- Pesquisa por:
  - Nome (Name)
  - Classe (Class)
  - Caminho (Path)
  - Todos (All)
- Filtros por serviços específicos do Roblox.
- Seleção direta dos resultados no Explorer do Roblox Studio.

### Memory
- Interface de monitoramento de memória.
- Exibição de informações relacionadas ao uso de memória.

## Arquitetura

O Instance Tracker utiliza uma arquitetura modular, separando as responsabilidades da Engine e da Interface.

```text
Instance-Tracker/
│
├── README.md
├── LICENSE
│
└── src/
    └── Instance Tracker/
        ├── Engine.luau
        ├── Interface.luau
        │
        └── Modules/
            ├── EventBus.luau
            ├── InstanceScanner.luau
            ├── InstanceWatcher.luau
            ├── Logger.luau
            ├── Memory.luau
            ├── PropertyWatcher.luau
            └── SearchEngine.luau
```

### EventBus

O EventBus é responsável pela comunicação entre a Engine e a Interface através de um sistema centralizado de eventos.

Essa abordagem mantém a interface independente da implementação interna dos módulos da Engine.

## Tecnologias utilizadas

- Luau
- Roblox Studio Plugin API
- Roblox Instance API
- Arquitetura orientada a eventos

## Instalação

1. Baixe ou clone este repositório.
2. Abra o Roblox Studio.
3. Instale o arquivo do plugin através do sistema de gerenciamento de plugins do Studio.
4. Ative o Instance Tracker.

*As instruções podem variar de acordo com o formato do plugin disponibilizado.*

## Status do projeto

**Versão:** 1.0

O Instance Tracker é um projeto em desenvolvimento contínuo. Novas funcionalidades e melhorias poderão ser adicionadas futuramente.

## Licença

Consulte o arquivo [LICENSE](LICENSE) para conhecer os termos de uso e distribuição.

---

# 🇺🇸 English

## About

**Instance Tracker** is a Roblox Studio plugin designed to help developers inspect, monitor and understand their game's Instance hierarchy through a centralized interface.

The project provides tools for hierarchy exploration, event monitoring, global searching and memory inspection.

## Features

### General
- Overview of tracked Instances.
- Activity monitoring.
- Quick access to important information.

### Explorer
- Browse the Instance hierarchy.
- Inspect objects and their structures.
- Monitor hierarchy changes.

### Event Logs
- Centralized logging system.
- Track Instance additions and removals.
- View recorded activity through the interface.

### Search
- Global Instance search.
- Search by:
  - Name
  - Class
  - Path
  - All
- Filter searches by specific Roblox services.
- Select search results directly in Roblox Studio's Explorer.

### Memory
- Memory monitoring interface.
- Display memory-related information.

## Architecture

Instance Tracker uses a modular architecture that separates the responsibilities of the Engine and Interface.

```text
Instance-Tracker/
│
├── README.md
├── LICENSE
│
└── src/
    └── Instance Tracker/
        ├── Engine.luau
        ├── Interface.luau
        │
        └── Modules/
            ├── EventBus.luau
            ├── InstanceScanner.luau
            ├── InstanceWatcher.luau
            ├── Logger.luau
            ├── Memory.luau
            ├── PropertyWatcher.luau
            └── SearchEngine.luau
```

### EventBus

The EventBus handles communication between the Engine and Interface through a centralized event system.

This approach keeps the interface independent from the internal implementation of the Engine modules.

## Technologies

- Luau
- Roblox Studio Plugin API
- Roblox Instance API
- Event-driven architecture

## Installation

1. Download or clone this repository.
2. Open Roblox Studio.
3. Install the plugin file through Studio's plugin management system.
4. Enable Instance Tracker.

*Installation instructions may vary depending on the distributed plugin format.*

## Project Status

**Version:** 1.0

Instance Tracker is an ongoing project. New features and improvements may be introduced over time.

## License

See the [LICENSE](LICENSE) file for usage and distribution terms.

---

**Developed by zTheo47**

