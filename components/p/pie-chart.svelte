<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnm6bw1lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vnm6bw1lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pie-chart" {...props}></Icon>
