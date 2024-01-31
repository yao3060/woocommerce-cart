# Woocommerce Cart

## Select the specific items on the cart page to proceed to checkout.

```php
	/**
	 * Gets cart contents.
	 *
	 * @since 3.2.0
	 * @return array of cart items
	 */
	public function get_cart_contents() {
		return apply_filters( 'woocommerce_get_cart_contents', (array) $this->cart_contents );
	}
```
