# Normalization 1NF - 3NF

Sebuah toko online menyimpan data transaksi pembelian dalam format berikut:

OrderID |	CustomerName	| CustomerAddress |	Items Purchased |	TotalPrice |
---| --| --| --|--
001	| Andi |	Jl. Mawar No. 1, Jakarta	| Laptop, Mouse	| 12000000 | 
002 |	Budi | Jl. Melati No. 2, Bogor |	Keyboard, Monitor, Headset |	4500000 |
003 |	Andi |	Jl. Mawar No. 1, Jakarta |	Flashdisk |	150000 |

Notes:
- Setiap order bisa memiliki lebih dari satu item.
- Customer dengan nama yang sama bisa muncul lebih dari sekali.
- Dapat menggunakan `excel` atau `spreadsheet` untuk memudahkan proses Normalisasi.
