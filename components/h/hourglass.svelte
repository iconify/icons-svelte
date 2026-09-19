<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0i0kbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":432};
const content = `<path class="bb0i0kbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hourglass" {...props}></Icon>
