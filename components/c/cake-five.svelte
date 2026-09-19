<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/lhlj3cbey.css';
import '../../css/q/qfxalsbxq.css';
import '../../css/j/jaoqwr_ai.css';
import '../../css/l/lo2z8bp4b.css';
import '../../css/s/sfs98y94q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="lhlj3cbey"/><path class="qfxalsbxq"/><path class="jaoqwr_ai"/><path class="lo2z8bp4b"/><path class="sfs98y94q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cake-five" {...props}></Icon>
