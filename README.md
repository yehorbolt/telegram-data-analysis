# Telegram data analysis
In 2013, an interesting Telegram messenger appeared, invented by Pavel Durov. He decided to test the technology of encrypted correspondence - MTProto, authored by his brother Nikolai Durov. Durov was interested in how the technology will cope with a heavy load. 
That's how the first version of the program appeared, which is still available on almost all platforms.

Nowadays, this messenger is an integral part of our online life, and a lot of data can be used for research.
In this situation, we used:
* **Database of messages from groups, private dialogues, channels.** (Dialogues id, send date, sender id, recipient id, message text, type)
* **Database of information about groups, private dialogues, channels.** (Participants, names, dialogue IDs, etc.)

# What do we get from this data?

* **Using the message database**
1. Comparison of the number of messages of individual types
2. Comparison of the total length of media messages
3. Find out the 5 most used stickers in messages
4. Compare the number of messages sent by me / the rest of the participants in the conversations.

* **Using the group information database**
1. Group/Private dialog /Channel ratio in Telegram
2. Compare first letters of private chat and group names

# Team

Bolotov Yehor,[yehorbolt](https://github.com/yehorbolt) 

# Instruction and requirements
