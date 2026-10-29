<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lg_nejb3d.css';
import '../../css/x/xnz7p-bku.css';
import '../../css/h/hbuj9d8ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lg_nejb3d wm-k"/><path class="wm-k xnz7p-bku"/><path class="hbuj9d8ju wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:car-front-sketch" {...props}></Icon>
