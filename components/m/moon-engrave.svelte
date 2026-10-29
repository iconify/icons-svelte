<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jt065lb1t.css';
import '../../css/a/aoqg6rbad.css';
import '../../css/s/sfp-qh-hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jt065lb1t"/><path class="aoqg6rbad wm-shadow"/><path class="sfp-qh-hh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:moon-engrave" {...props}></Icon>
