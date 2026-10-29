<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xyj51-3yi.css';
import '../../css/u/uwvegzi1z.css';
import '../../css/s/shsa3e98e.css';
import '../../css/k/kgcxnxbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xyj51-3yi"/><path class="uwvegzi1z wm-a"/><path class="shsa3e98e wm-k"/><path class="kgcxnxbyj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refresh-sketch" {...props}></Icon>
