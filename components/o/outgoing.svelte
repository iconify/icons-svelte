<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uhzhoz_lg.css';
import '../../css/t/t1l8wac3t.css';
import '../../css/i/iucmbeysh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="uhzhoz_lg"/><path class="t1l8wac3t"/><path class="iucmbeysh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:outgoing" {...props}></Icon>
