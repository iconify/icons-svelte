<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0dsanjek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g0dsanjek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-currency-dollar-dollar-exchange-payment-forex-finance-currency-money-foreign" {...props}></Icon>
