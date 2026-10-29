<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m3fhfrafa.css';
import '../../css/s/srec5cclg.css';
import '../../css/r/rojp4pxea.css';
import '../../css/a/a91ndtnyb.css';
import '../../css/s/sqx3j0bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m3fhfrafa wm-k"/><path class="srec5cclg wm-shadow"/><path class="rojp4pxea wm-k"/><path class="a91ndtnyb wm-k"/><path class="sqx3j0bau wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:package-engrave" {...props}></Icon>
