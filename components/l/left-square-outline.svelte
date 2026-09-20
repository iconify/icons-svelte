<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3k4mxcjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j3k4mxcjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:left-square-outline" {...props}></Icon>
