<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb6xndjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="rnb6xndjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:filter-tilt-shift" {...props}></Icon>
