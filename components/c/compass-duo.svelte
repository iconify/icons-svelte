<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oan3fnbps.css';
import '../../css/z/z1c1vtbba.css';
import '../../css/u/uesbikcft.css';
import '../../css/y/yw4fz_b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="oan3fnbps"/><path class="wm-a z1c1vtbba"/><path class="uesbikcft wm-a"/><path class="yw4fz_b6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:compass-duo" {...props}></Icon>
