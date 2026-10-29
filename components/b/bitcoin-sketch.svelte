<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r0k_789eh.css';
import '../../css/z/zgq5wtbpl.css';
import '../../css/k/k119jwb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r0k_789eh wm-k"/><path class="wm-k zgq5wtbpl"/><path class="k119jwb1b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bitcoin-sketch" {...props}></Icon>
