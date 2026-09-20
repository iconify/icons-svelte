<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orng1hbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="orng1hbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-cash-bag-bag-payment-cash-money-finance" {...props}></Icon>
