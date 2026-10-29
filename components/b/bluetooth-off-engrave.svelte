<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oor6kibka.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/p/p928l8bmr.css';
import '../../css/a/ahz5bx2fp.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oor6kibka wm-k"/><path class="ol-kpp5cg wm-s"/><path class="p928l8bmr wm-shadow"/><path class="ahz5bx2fp wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bluetooth-off-engrave" {...props}></Icon>
