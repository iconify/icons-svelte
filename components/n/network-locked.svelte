<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coghedhns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":456};
const content = `<path class="coghedhns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-locked" {...props}></Icon>
