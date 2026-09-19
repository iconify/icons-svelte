<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm4lw1-pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm4lw1-pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:pie-chart-outline-25" {...props}></Icon>
