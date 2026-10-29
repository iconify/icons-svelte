<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/drgourb2x.css';
import '../../css/e/ee72xe_hx.css';
import '../../css/b/bt4eanb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="drgourb2x"/><path class="ee72xe_hx wm-a"/><path class="bt4eanb_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-2-duo" {...props}></Icon>
