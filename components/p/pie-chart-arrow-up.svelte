<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtse6qx-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtse6qx-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pie-chart-arrow-up" {...props}></Icon>
