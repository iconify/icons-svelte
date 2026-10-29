<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_jv868wi.css';
import '../../css/b/b46u89b7h.css';
import '../../css/v/v8bw9nbrg.css';
import '../../css/l/lhr7mp78x.css';
import '../../css/r/rad68db9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_jv868wi wm-k"/><path class="b46u89b7h wm-a"/><path class="v8bw9nbrg wm-shadow"/><path class="lhr7mp78x wm-k"/><path class="rad68db9z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-rain-wind-engrave" {...props}></Icon>
