<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g5dvq_klh.css';
import '../../css/p/p68pgcbjk.css';
import '../../css/l/lzad66der.css';
import '../../css/s/sc6ko9v-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g5dvq_klh"/><path class="p68pgcbjk wm-a"/><path class="lzad66der wm-k"/><path class="sc6ko9v-k wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cherry-sketch" {...props}></Icon>
