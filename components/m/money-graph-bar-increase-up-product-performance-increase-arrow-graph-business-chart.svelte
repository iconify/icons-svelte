<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv_rmbk8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zv_rmbk8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-graph-bar-increase-up-product-performance-increase-arrow-graph-business-chart" {...props}></Icon>
