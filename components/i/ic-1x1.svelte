<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/n/ncw4z3bwh.css';
import '../../css/w/wps4e9ynm.css';
import '../../css/f/fz7419b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="ncw4z3bwh"/><path class="wps4e9ynm"/><path class="fz7419b1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ic-1x1" {...props}></Icon>
