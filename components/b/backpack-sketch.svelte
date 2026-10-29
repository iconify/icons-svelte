<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/naz7nhbla.css';
import '../../css/q/qwyktibri.css';
import '../../css/o/onacwcrjs.css';
import '../../css/p/px7dfaclp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="naz7nhbla"/><path class="qwyktibri wm-a"/><path class="onacwcrjs wm-k"/><path class="px7dfaclp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:backpack-sketch" {...props}></Icon>
