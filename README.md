# WhitePaper  

**zk Bank**  

Project developed to provide security to the user founds using zero-knowledge technology   
 - Functions:   
	The user have a token valued and needs project using a secondary layer   
	 Similar a swap pool, the founds are deposited inside a new contract   
	 the new contract will store the user liquidity and will lock   
   the user will receive zkBank tokens   
	 he will can swap again zkBank tokens per your original token stored in Layer Two  
 	 

---

### 🧠 **Zero-Knowledge Proofs (ZKPs)**

At the core of many zk-based technologies is the **zero-knowledge proof**, which lets one party prove to another that a statement is true without revealing *why* it's true. In blockchain, ZKPs are mainly used to enhance **scalability** and **privacy**.

---

### ⚙️ **zkEVM (Zero-Knowledge Ethereum Virtual Machine)**

A **zkEVM** is a type of zk-rollup that can run Ethereum-compatible smart contracts (EVM bytecode) but still benefits from zero-knowledge proofs. It validates transactions off-chain and submits a succinct proof to Ethereum.

- **Goal**: Ethereum scalability without changing existing code or developer tooling.
- **Projects working on zkEVMs**:
  - **Polygon zkEVM**
  - **Scroll**
  - **zkSync Era**
  - **Consensys zkEVM**

---

### 🌀 **zkSync**

A **Layer 2 scaling solution** built on Ethereum, zkSync comes in two main flavors:

1. **zkSync Lite** – focused on payments, already live.
2. **zkSync Era** – a zkEVM designed to support general smart contracts.

**zkSync Era** enables developers to deploy smart contracts using familiar Solidity code and get scalability + security benefits via ZKPs.

Key features:
- EVM-compatible (but not bytecode-equivalent yet)
- Faster, cheaper transactions
- Validity proofs for security

---

### 🧱 **ZK Layer 2s**

**ZK Layer 2** refers to any scaling solution that uses ZKPs to post validity proofs to Ethereum. They're part of the **rollup family**, and generally offer:

- **Faster throughput**
- **Lower gas fees**
- **Stronger security assumptions** than optimistic rollups (no fraud window)

---

Would you like a comparison with optimistic rollups, or a deep dive into how zkEVMs generate and verify proofs?
