<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jcs245bfb.css';
import '../../css/p/plhtj7b7c.css';
import '../../css/e/e0cmz0boh.css';
import '../../css/z/zr35ecbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jcs245bfb"/><path class="plhtj7b7c"/><path class="e0cmz0boh"/><path class="zr35ecbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-video-camera-linear" {...props}></Icon>
