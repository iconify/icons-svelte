<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/krl86btlo.css';
import '../../css/l/lbhtagbyq.css';
import '../../css/u/uewg3bcmw.css';
import '../../css/m/mmh2-406e.css';
import '../../css/u/u4plrgndh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="krl86btlo"/><path class="lbhtagbyq wm-k"/><path class="uewg3bcmw wm-a"/><path class="mmh2-406e wm-k"/><path class="u4plrgndh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:droplets-sketch" {...props}></Icon>
