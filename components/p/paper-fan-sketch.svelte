<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mejzk5lgr.css';
import '../../css/r/ropvj0mrx.css';
import '../../css/h/h3koi8h_e.css';
import '../../css/i/iyajw1yez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mejzk5lgr wm-k"/><path class="ropvj0mrx wm-k"/><path class="h3koi8h_e wm-a"/><circle class="iyajw1yez wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paper-fan-sketch" {...props}></Icon>
