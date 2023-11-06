# Programming-Fundamentals-in-Kotlin

This course taught me how to use Kotlin, a powerful and expressive programming language, to create apps for Android Auto.These skills will help me in my dream of developing apps that make driving safer and more enjoyable on Android Auto.

# Overview of technical assignment 

This Kotlin code defines a simple text-based banking system. Here's a technical specification of what the code does in layman's terms:

1. The code starts with an empty account type.

2. The `main` function is the entry point for the program.

3. Inside the `main` function, it does the following:
   - It generates a random initial account balance between 0 and 1000 dollars.
   - It generates a random amount of money to be transferred.
   - It defines a variable `output` and calls the `withdraw` function, which deducts the specified amount from the account balance and updates it. It prints the withdrawal amount and the new balance.
   - It then calls the `debitWithdraw` function, which allows for a special case handling of withdrawals, considering the account type and balance. It prints the withdrawal amount and the new balance or appropriate messages.
   - It calls the `deposit` function, which adds the specified amount to the account balance and updates it. It prints the deposit amount and the new balance.
   - Finally, it calls the `creditDeposit` function, which handles deposits based on the account type, considering special cases. It prints the deposit amount and the new balance or appropriate messages.

4. The `transfer` function is defined to manage withdrawals and deposits based on a specified mode ("withdraw" or "deposit"). It checks the account type and calls the appropriate withdrawal or deposit function. It prints the transferred amount.

5. It sets up a loop to interact with the user while the system is open. It presents a menu with options to:
   - Check the account balance.
   - Withdraw money.
   - Deposit money.
   - Close the system.

6. The user selects an option, and based on their choice, it either displays the account balance, initiates a withdrawal or deposit using the `transfer` function, or closes the system.

7. The `accountTypeSelector` function is used to prompt the user to choose an account type (debit, credit, or checking) and stores the selected type in the `accountType` variable.

In summary, this code simulates a basic banking system where users can create an account, check their balance, withdraw money, and deposit money. The code handles different scenarios based on the chosen account type and ensures that the user interacts with the system until they choose to close it.
