<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pk11pab5e.css';
import '../../css/k/kye7fgb5m.css';
import '../../css/o/oxol8u2xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pk11pab5e"/><path class="kye7fgb5m wm-a"/><path class="oxol8u2xx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dices" {...props}></Icon>
