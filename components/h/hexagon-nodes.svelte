<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imh-7cbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="imh-7cbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hexagon-nodes" {...props}></Icon>
