<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pmgr_fqgg.css';
import '../../css/g/gpu50ftma.css';
import '../../css/s/s36pesbba.css';
import '../../css/e/enuleymwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pmgr_fqgg wm-k"/><path class="gpu50ftma wm-a"/><path class="s36pesbba wm-k"/><path class="enuleymwy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:redo-sketch" {...props}></Icon>
