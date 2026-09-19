<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3dpzbtra.css';
import '../../css/z/zhcnnrbqz.css';
import '../../css/y/yg0-h_7ex.css';
import '../../css/o/oric6vbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="zhcnnrbqz"/><path class="yg0-h_7ex"/><path class="oric6vbzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:arena" {...props}></Icon>
