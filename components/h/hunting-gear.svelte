<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zt58lacpe.css';
import '../../css/m/mzhpw8m7u.css';
import '../../css/r/ru8717ryg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="zt58lacpe"/><path class="mzhpw8m7u"/><path class="ru8717ryg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hunting-gear" {...props}></Icon>
