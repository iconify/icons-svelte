<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zbsyr1dde.css';
import '../../css/f/fu-yhsexq.css';
import '../../css/d/d5ox4i4-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zbsyr1dde"/><path class="fu-yhsexq"/><path class="d5ox4i4-t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hospital" {...props}></Icon>
