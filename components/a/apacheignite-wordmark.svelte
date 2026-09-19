<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbds7eckz.css';
import '../../css/p/p6kfs-93h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xbds7eckz"/><path class="p6kfs-93h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apacheignite-wordmark" {...props}></Icon>
