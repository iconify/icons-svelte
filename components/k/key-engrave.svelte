<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kqeyp4k-t.css';
import '../../css/c/cbqvu9b5z.css';
import '../../css/x/xpmjmd9yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kqeyp4k-t"/><path class="cbqvu9b5z wm-shadow"/><path class="xpmjmd9yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:key-engrave" {...props}></Icon>
