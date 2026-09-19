<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g90-vg5gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g90-vg5gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:airplane" {...props}></Icon>
