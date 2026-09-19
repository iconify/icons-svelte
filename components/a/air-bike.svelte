<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xr59g6zsq.css';
import '../../css/v/v4m-gobyd.css';
import '../../css/o/odvo2bwsa.css';
import '../../css/p/pywn4zp7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xr59g6zsq"/><circle class="v4m-gobyd"/><path class="odvo2bwsa"/><path class="pywn4zp7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:air-bike" {...props}></Icon>
