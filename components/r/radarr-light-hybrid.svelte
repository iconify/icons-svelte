<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-71aubjb.css';
import '../../css/f/f24w92bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-71aubjb"/><path class="f24w92bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-light-hybrid" {...props}></Icon>
