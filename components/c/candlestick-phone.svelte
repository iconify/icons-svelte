<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co3vs6bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co3vs6bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:candlestick-phone" {...props}></Icon>
