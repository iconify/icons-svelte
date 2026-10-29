<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t7wgm3bcf.css';
import '../../css/d/duwkm8_od.css';
import '../../css/r/re13p-ksd.css';
import '../../css/e/eyw-z6bdb.css';
import '../../css/b/by-5tbcoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t7wgm3bcf"/><path class="duwkm8_od wm-k"/><path class="re13p-ksd wm-a"/><path class="eyw-z6bdb wm-k"/><path class="by-5tbcoa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-plus-sketch" {...props}></Icon>
