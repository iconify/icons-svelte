<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vgn90vbzq.css';
import '../../css/q/qrlq0qbok.css';
import '../../css/q/q9vrskbqf.css';
import '../../css/o/ou91-ob5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vgn90vbzq"/><path class="qrlq0qbok wm-k"/><path class="q9vrskbqf wm-a"/><path class="ou91-ob5b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-up-sketch" {...props}></Icon>
