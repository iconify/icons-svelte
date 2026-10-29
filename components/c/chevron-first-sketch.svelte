<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h7c3qx-ae.css';
import '../../css/u/uwi6pe5sg.css';
import '../../css/p/p_w6bcb-q.css';
import '../../css/r/rj25d81vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h7c3qx-ae wm-k"/><path class="uwi6pe5sg wm-a"/><path class="p_w6bcb-q wm-k"/><path class="rj25d81vo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-first-sketch" {...props}></Icon>
