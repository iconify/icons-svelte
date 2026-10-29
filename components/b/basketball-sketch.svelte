<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bc2a5pb0l.css';
import '../../css/t/timyirbcb.css';
import '../../css/l/lf5_obwyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bc2a5pb0l"/><path class="timyirbcb wm-k"/><path class="lf5_obwyo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:basketball-sketch" {...props}></Icon>
