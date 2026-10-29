<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vghtvybyf.css';
import '../../css/s/smls78shz.css';
import '../../css/i/ic5g_yble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vghtvybyf"/><path class="smls78shz wm-a"/><path class="ic5g_yble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:door-closed-duo" {...props}></Icon>
