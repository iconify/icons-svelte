<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t_vg7vytr.css';
import '../../css/q/qvpo85bgg.css';
import '../../css/q/qzof9nhok.css';
import '../../css/u/u5j49objb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t_vg7vytr wm-k"/><path class="qvpo85bgg wm-shadow"/><path class="qzof9nhok wm-k"/><path class="u5j49objb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:beef-engrave" {...props}></Icon>
