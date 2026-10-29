<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gpylk-uae.css';
import '../../css/v/vp02ces9z.css';
import '../../css/q/qwrl1299h.css';
import '../../css/t/tp8x2imva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gpylk-uae wm-a"/><path class="vp02ces9z wm-a"/><path class="qwrl1299h"/><path class="tp8x2imva wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:beer-duo" {...props}></Icon>
