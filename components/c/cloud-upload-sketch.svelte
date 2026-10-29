<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f2muu1bnt.css';
import '../../css/p/pnyxl532q.css';
import '../../css/u/uqh-4c7rl.css';
import '../../css/n/npzunlt5o.css';
import '../../css/i/ik3xy0-cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f2muu1bnt"/><path class="pnyxl532q wm-k"/><path class="uqh-4c7rl wm-k"/><path class="npzunlt5o wm-s"/><path class="ik3xy0-cl wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-upload-sketch" {...props}></Icon>
