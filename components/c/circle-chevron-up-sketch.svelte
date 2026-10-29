<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xzizubbgh.css';
import '../../css/n/n5bw5rb1s.css';
import '../../css/v/vd_sncc5p.css';
import '../../css/p/pui78qb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xzizubbgh"/><path class="n5bw5rb1s wm-a"/><path class="vd_sncc5p wm-k"/><path class="pui78qb2p wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-chevron-up-sketch" {...props}></Icon>
