<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv1i2gnkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zv1i2gnkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-currency-euro-exchange-payment-euro-forex-finance-currency-money-foreign" {...props}></Icon>
