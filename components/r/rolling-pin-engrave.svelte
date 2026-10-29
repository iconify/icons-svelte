<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/erpaaj0nr.css';
import '../../css/j/jgyokzbac.css';
import '../../css/r/r43my2bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="erpaaj0nr"/><path class="jgyokzbac wm-shadow"/><path class="r43my2bli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rolling-pin-engrave" {...props}></Icon>
