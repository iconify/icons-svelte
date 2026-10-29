<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xw_l8jjfs.css';
import '../../css/s/saqexskah.css';
import '../../css/o/oah_nmb4a.css';
import '../../css/r/rumhxo9iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xw_l8jjfs"/><path class="saqexskah wm-k"/><path class="oah_nmb4a wm-k"/><path class="rumhxo9iv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-lightning-sketch" {...props}></Icon>
