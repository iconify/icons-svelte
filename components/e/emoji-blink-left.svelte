<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tvo3ulbme.css';
import '../../css/x/xpwwbpbtk.css';
import '../../css/e/efsv_hb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvo3ulbme"/><path class="xpwwbpbtk"/><path class="efsv_hb2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:emoji-blink-left" {...props}></Icon>
