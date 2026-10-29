<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zy9xw0nee.css';
import '../../css/g/g2ivodb2f.css';
import '../../css/v/vt-2nu9uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wm-a zy9xw0nee"/><path class="g2ivodb2f"/><path class="vt-2nu9uw wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:firecracker-string" {...props}></Icon>
