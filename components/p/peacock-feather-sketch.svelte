<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xa_x1dbjv.css';
import '../../css/d/dlhe9xb0h.css';
import '../../css/p/p9ineh26q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xa_x1dbjv"/><path class="dlhe9xb0h wm-k"/><path class="p9ineh26q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:peacock-feather-sketch" {...props}></Icon>
