<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbgqgkb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sbgqgkb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-above-outstretched-hand" {...props}></Icon>
