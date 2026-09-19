<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rcxs0t6qt.css';
import '../../css/c/c22h241vp.css';
import '../../css/s/squd7s8xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="rcxs0t6qt"/><circle class="c22h241vp"/><path class="squd7s8xm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:editing" {...props}></Icon>
