<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cblyjfbfa.css';
import '../../css/t/tzb2l-bbx.css';
import '../../css/l/lsvuykfaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cblyjfbfa"/><path class="tzb2l-bbx"/><circle transform="rotate(25 12.083 36.688)" class="lsvuykfaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:google-ads" {...props}></Icon>
