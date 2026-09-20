<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wkamaxf.css';
import '../../css/f/f24w92bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="f24w92bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr" {...props}></Icon>
