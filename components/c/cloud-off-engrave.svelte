<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ctxblysyk.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/u/ugrmfyzgf.css';
import '../../css/s/shi8u7lan.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ctxblysyk wm-k"/><path class="ol-kpp5cg wm-s"/><path class="ugrmfyzgf wm-shadow"/><path class="shi8u7lan wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-off-engrave" {...props}></Icon>
