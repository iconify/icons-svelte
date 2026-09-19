<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/r8cyu3bwz.css';
import '../../css/q/q-vig9vwl.css';
import '../../css/s/sl781pbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="r8cyu3bwz"/><path class="q-vig9vwl"/><path class="sl781pbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:powerpoint" {...props}></Icon>
