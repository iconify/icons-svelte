<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f-uum3e5i.css';
import '../../css/y/y57j-w5pv.css';
import '../../css/r/ru4tp72_w.css';
import '../../css/c/c91spwb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f-uum3e5i"/><path class="wm-shadow y57j-w5pv"/><path class="ru4tp72_w"/><path class="c91spwb6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gem-engrave" {...props}></Icon>
