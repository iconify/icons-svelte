<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zq1sn1yld.css';
import '../../css/i/i9sk41bib.css';
import '../../css/s/ss5svr9ob.css';
import '../../css/q/q3o42wsez.css';
import '../../css/v/vrvs2074r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zq1sn1yld"/><path class="i9sk41bib wm-s"/><path class="ss5svr9ob wm-shadow"/><path class="q3o42wsez wm-k"/><path class="vrvs2074r wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:remove-formatting-engrave" {...props}></Icon>
