<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/s/slbbecb5f.css';
import '../../css/l/lymwctbiv.css';
import '../../css/w/wwhng8org.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="d2kvgvbvc"><path class="slbbecb5f"/><path class="lymwctbiv"/><path class="wwhng8org"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ml-1x1" {...props}></Icon>
