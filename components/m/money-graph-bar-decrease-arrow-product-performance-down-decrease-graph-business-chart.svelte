<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs6j3rbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vs6j3rbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-graph-bar-decrease-arrow-product-performance-down-decrease-graph-business-chart" {...props}></Icon>
