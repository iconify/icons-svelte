<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/n03w5kbkh.css';
import '../../css/q/qseas_bes.css';
import '../../css/v/ve4z9yd-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="n03w5kbkh"/><path class="qseas_bes"/><path class="ve4z9yd-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:f-nine-key" {...props}></Icon>
