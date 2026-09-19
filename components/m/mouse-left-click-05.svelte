<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/d-_v3vaqc.css';
import '../../css/x/xhce_hbyg.css';
import '../../css/j/jx0woobce.css';
import '../../css/l/lzkg2p4uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="d-_v3vaqc"/><path class="xhce_hbyg"/><path class="jx0woobce"/><circle class="lzkg2p4uu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-left-click-05" {...props}></Icon>
