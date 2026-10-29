<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fpdd2ab7l.css';
import '../../css/z/zl8syfbae.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/h/hbi8hhkfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fpdd2ab7l"/><path class="wm-a zl8syfbae"/><path class="yw4fz_b6b"/><path class="hbi8hhkfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:donut-duo" {...props}></Icon>
