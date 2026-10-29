<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w4_v3tb5k.css';
import '../../css/t/t5vfqvb6r.css';
import '../../css/c/cm3qj-lzz.css';
import '../../css/t/t1lo1jbjx.css';
import '../../css/d/doa5x-b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w4_v3tb5k"/><path class="t5vfqvb6r wm-k"/><path class="cm3qj-lzz wm-a"/><path class="t1lo1jbjx wm-k"/><path class="doa5x-b0h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pilcrow-sketch" {...props}></Icon>
