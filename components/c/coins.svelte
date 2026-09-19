<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gy66vxd3l.css';
import '../../css/q/q1tfifwlw.css';
import '../../css/b/bwm3foqlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gy66vxd3l"/><path class="q1tfifwlw"/><path class="bwm3foqlw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:coins" {...props}></Icon>
