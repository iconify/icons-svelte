<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3dpzbtra.css';
import '../../css/b/ble3jubnc.css';
import '../../css/w/ww18m3b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="ble3jubnc"/><path class="ww18m3b3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:curling" {...props}></Icon>
