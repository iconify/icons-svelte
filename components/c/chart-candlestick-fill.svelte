<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckohrz7gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckohrz7gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-candlestick-fill" {...props}></Icon>
