<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnooe-boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vnooe-boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:convex-hull" {...props}></Icon>
