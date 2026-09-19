<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/r8cyu3bwz.css';
import '../../css/d/dkty4hkoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="r8cyu3bwz"/><path class="dkty4hkoy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:excel-one" {...props}></Icon>
