<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i_fhoxbnq.css';
import '../../css/z/z-tizms8b.css';
import '../../css/z/z67pmyrnw.css';
import '../../css/i/i-e0xfb7g.css';
import '../../css/j/j_5p8mbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i_fhoxbnq"/><path class="wm-a z-tizms8b"/><path class="wm-a z67pmyrnw"/><path class="i-e0xfb7g"/><path class="j_5p8mbom wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-coins-duo" {...props}></Icon>
