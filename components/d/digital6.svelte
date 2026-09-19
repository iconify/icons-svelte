<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j21hu4qcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j21hu4qcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital6" {...props}></Icon>
