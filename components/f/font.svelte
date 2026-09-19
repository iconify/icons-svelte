<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccq_gd3ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ccq_gd3ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:font" {...props}></Icon>
