<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m1i7o_bwx.css';
import '../../css/v/vnrag9skx.css';
import '../../css/m/mozr6bcby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m1i7o_bwx"/><path class="vnrag9skx"/><path class="mozr6bcby wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:microphone-duo" {...props}></Icon>
