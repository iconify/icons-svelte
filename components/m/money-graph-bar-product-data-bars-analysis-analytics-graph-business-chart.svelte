<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po7q84-3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="po7q84-3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-graph-bar-product-data-bars-analysis-analytics-graph-business-chart" {...props}></Icon>
