<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bsuy9b0zv.css';
import '../../css/q/qoldq5b5w.css';
import '../../css/z/zagc9leuw.css';
import '../../css/v/vkffuubtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bsuy9b0zv wm-k"/><path class="qoldq5b5w wm-a"/><path class="wm-k zagc9leuw"/><path class="vkffuubtt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:container-sketch" {...props}></Icon>
