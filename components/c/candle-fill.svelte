<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0anmy__x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0anmy__x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candle-fill" {...props}></Icon>
