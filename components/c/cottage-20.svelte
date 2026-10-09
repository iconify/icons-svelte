<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwuvbdcau.css';
import '../../css/y/yow8pow4g.css';
import '../../css/t/tgtgovnso.css';
import '../../css/b/b0mt28bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bwuvbdcau"/><path class="yow8pow4g"/><path class="tgtgovnso"/><path class="b0mt28bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cottage-20" {...props}></Icon>
