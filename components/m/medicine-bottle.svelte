<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/ipf2vu9op.css';
import '../../css/f/fzm2rccme.css';
import '../../css/p/p_61p5bej.css';
import '../../css/b/btj-cobvn.css';
import '../../css/t/t6-8_dbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ipf2vu9op"/><path class="fzm2rccme"/><path class="p_61p5bej"/><path class="btj-cobvn"/><path class="t6-8_dbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:medicine-bottle" {...props}></Icon>
