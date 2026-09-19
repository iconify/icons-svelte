<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqcne8d0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqcne8d0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:candlestick-chart" {...props}></Icon>
