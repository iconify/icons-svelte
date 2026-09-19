<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/ctq-00ygq.css';
import '../../css/g/g0flr5bpr.css';
import '../../css/x/xm8fyk4mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ctq-00ygq"/><circle class="g0flr5bpr"/><path class="xm8fyk4mu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-block" {...props}></Icon>
