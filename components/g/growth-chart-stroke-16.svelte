<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8d3vob2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y8d3vob2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:growth-chart-stroke-16" {...props}></Icon>
