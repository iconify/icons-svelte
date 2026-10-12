<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcbbl7i3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dcbbl7i3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubbles-stroke-20" {...props}></Icon>
