<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmiz98b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmiz98b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-candle" {...props}></Icon>
