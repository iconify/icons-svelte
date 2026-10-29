<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qxum5lb5g.css';
import '../../css/c/cz6jy1boo.css';
import '../../css/q/qvx_ar2cl.css';
import '../../css/c/cjivcabhf.css';
import '../../css/i/ivj0dyb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qxum5lb5g wm-k"/><path class="cz6jy1boo wm-a"/><path class="qvx_ar2cl wm-shadow"/><path class="cjivcabhf wm-k"/><path class="ivj0dyb1p wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cursor-engrave" {...props}></Icon>
