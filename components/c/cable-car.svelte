<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0c2d3bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0c2d3bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cable-car" {...props}></Icon>
