<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itinflbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="itinflbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-currency-bitcoin-crypto-circle-payment-blokchain-finance-bitcoin-currency-money" {...props}></Icon>
