<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g3oicd9zy.css';
import '../../css/w/w6urksb-q.css';
import '../../css/h/ht8ohn1mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g3oicd9zy"/><path class="w6urksb-q"/><path class="ht8ohn1mx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:disk" {...props}></Icon>
