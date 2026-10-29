<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uzms2zbds.css';
import '../../css/s/swmyrlbhw.css';
import '../../css/e/ek7r2gmod.css';
import '../../css/i/ifw3mkwyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uzms2zbds wm-k"/><path class="swmyrlbhw wm-a"/><path class="ek7r2gmod wm-k"/><path class="ifw3mkwyi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:indent-increase-sketch" {...props}></Icon>
