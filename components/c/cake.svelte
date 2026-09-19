<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bh_y89zfc.css';
import '../../css/a/ahudpqbba.css';
import '../../css/b/byxdlpbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bh_y89zfc"/><path class="ahudpqbba"/><path class="byxdlpbyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:cake" {...props}></Icon>
