<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n0hxhlb-h.css';
import '../../css/l/l-l2pfuww.css';
import '../../css/y/y-uaqkbak.css';
import '../../css/r/rp9nrr50p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n0hxhlb-h"/><path class="l-l2pfuww wm-a"/><path class="wm-k y-uaqkbak"/><path class="rp9nrr50p wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contrast-sketch" {...props}></Icon>
