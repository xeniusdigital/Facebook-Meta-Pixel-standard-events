# Facebook-Meta-Pixel-standard-events

Standard events
Website action	Description	Standard event code
Add payment info	The addition of customer payment information during a checkout process. For example, a person clicks on a button to save their billing information.	fbq('track', 'AddPaymentInfo');

Add to cart	The addition of an item to a shopping cart or basket. For example, clicking an Add to Cart button on a website.	
fbq('track', 'AddToCart');

Add to wishlist	The addition of items to a wishlist. For example, clicking an Add to Wishlist button on a website.	
fbq('track', 'AddToWishlist');

Complete registration	A submission of information by a customer in exchange for a service provided by your business. For example, signing up for an email subscription.	fbq('track', 'CompleteRegistration');

Contact	A telephone, SMS, email, chat or other type of contact between a customer and your business.	
fbq('track', 'Contact');

Customize product	The customization of products through a configuration tool or other application your business owns.	
fbq('track', 'CustomizeProduct');

Donate	The donation of funds to your organization or cause.	
fbq('track', 'Donate');

Find location	When a person finds one of your locations via web, with an intention to visit. For example, searching for a product and finding it at one of your local stores.	
fbq('track', 'FindLocation');

Initiate checkout	The start of a checkout process. For example, clicking a Checkout button.	
fbq('track', 'InitiateCheckout');

Lead	A submission of information by a customer with the understanding that they may be contacted at a later date by your business. 
For example, submitting a form or signing up for a trial.	
fbq('track', 'Lead');

Purchase	The completion of a purchase, usually signified by receiving order or purchase confirmation, or a transaction receipt. For example, landing on a Thank You or confirmation page.	
fbq('track', 'Purchase', {value: 0.00, currency: 'USD'});

Schedule	The booking of an appointment to visit one of your locations.	
fbq('track', 'Schedule');

Search	A search performed on your website, app or other property. For example, product or travel searches.	
fbq('track', 'Search');

Start trial	The start of a free trial of a product or service you offer. For example, trial subscription.	
fbq('track', 'StartTrial', {value: '0.00', currency: 'USD', predicted_ltv: '0.00'});

Submit application	The submission of an application for a product, service or program you offer. For example, a credit card, educational program or job.	
fbq('track', 'SubmitApplication');

Subscribe	The start of a paid subscription for a product or service you offer.	
fbq('track', 'Subscribe', {value: '0.00', currency: 'USD', predicted_ltv: '0.00'});

View content	A visit to a web page you care about. For example, a product or landing page. View content tells you if someone visits a web page's URL, but not what they do or see on that web page.	
fbq('track', 'ViewContent');

https://www.facebook.com/business/help/402791146561655?id=1205376682832142
