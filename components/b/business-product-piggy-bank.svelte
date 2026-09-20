<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n60pvibmo.css';
import '../../css/k/kouf8lb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n60pvibmo"/><path class="kouf8lb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-product-piggy-bank" {...props}></Icon>
