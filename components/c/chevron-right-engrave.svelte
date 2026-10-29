<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/da795db8g.css';
import '../../css/w/wl3vkgwgq.css';
import '../../css/r/rat7bsbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="da795db8g"/><path class="wl3vkgwgq wm-shadow"/><path class="rat7bsbmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-right-engrave" {...props}></Icon>
