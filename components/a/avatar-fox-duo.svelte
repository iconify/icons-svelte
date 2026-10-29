<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xc0tnob1v.css';
import '../../css/j/jxh_h4rlc.css';
import '../../css/x/x34umyuqw.css';
import '../../css/m/mr8d_cbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xc0tnob1v"/><path class="jxh_h4rlc"/><path class="wm-a x34umyuqw"/><path class="mr8d_cbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-fox-duo" {...props}></Icon>
