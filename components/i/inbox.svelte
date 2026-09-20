<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgtg07bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xgtg07bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:inbox" {...props}></Icon>
