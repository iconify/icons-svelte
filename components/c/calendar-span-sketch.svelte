<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pcsz0c02v.css';
import '../../css/n/n8kpz1zht.css';
import '../../css/b/bi-ep5baw.css';
import '../../css/e/eyqtot1bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pcsz0c02v wm-k"/><path class="n8kpz1zht wm-a"/><path class="bi-ep5baw wm-k"/><path class="eyqtot1bt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-span-sketch" {...props}></Icon>
