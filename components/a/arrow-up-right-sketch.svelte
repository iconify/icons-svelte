<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pk375cb2c.css';
import '../../css/r/rnvgfonpn.css';
import '../../css/s/ssx8dqarr.css';
import '../../css/w/wqssnhx9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pk375cb2c wm-k"/><path class="rnvgfonpn wm-a"/><path class="ssx8dqarr wm-k"/><path class="wm-a wqssnhx9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-right-sketch" {...props}></Icon>
