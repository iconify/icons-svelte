<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lo1tr_b1c.css';
import '../../css/n/na3rfosvr.css';
import '../../css/j/jgz8mubms.css';
import '../../css/w/w62x13bmw.css';
import '../../css/r/rsai_abhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lo1tr_b1c wm-k"/><path class="na3rfosvr wm-a"/><path class="jgz8mubms wm-shadow"/><path class="w62x13bmw wm-k"/><path class="rsai_abhp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:airplay-engrave" {...props}></Icon>
