<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lfcmlbvrc.css';
import '../../css/m/mboxxfb9b.css';
import '../../css/e/esaiihsdv.css';
import '../../css/v/vqk9ftbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lfcmlbvrc wm-k"/><path class="mboxxfb9b wm-a"/><path class="esaiihsdv wm-k"/><path class="vqk9ftbxk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lollipop-sketch" {...props}></Icon>
