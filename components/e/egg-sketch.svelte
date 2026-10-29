<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vuf7_xbay.css';
import '../../css/i/iq3a_n6pb.css';
import '../../css/s/svzookb7d.css';
import '../../css/s/s37zpibbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vuf7_xbay"/><path class="iq3a_n6pb wm-a"/><path class="svzookb7d wm-k"/><path class="s37zpibbo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:egg-sketch" {...props}></Icon>
