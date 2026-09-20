<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnmr5yb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fnmr5yb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excalidraw-light" {...props}></Icon>
