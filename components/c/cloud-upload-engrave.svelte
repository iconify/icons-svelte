<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sxie_rsic.css';
import '../../css/w/wm_kbibqc.css';
import '../../css/y/y7q976lkn.css';
import '../../css/m/m2ebxhp-u.css';
import '../../css/g/gpzldrb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sxie_rsic wm-k"/><path class="wm-s wm_kbibqc"/><path class="wm-shadow y7q976lkn"/><path class="m2ebxhp-u wm-k"/><path class="gpzldrb9z wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-upload-engrave" {...props}></Icon>
