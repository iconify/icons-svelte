<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/prnexjb1i.css';
import '../../css/r/rvo8e2pwf.css';
import '../../css/l/lx6vztc2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="prnexjb1i"/><path class="rvo8e2pwf wm-shadow"/><path class="lx6vztc2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-desk-engrave" {...props}></Icon>
