<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rq7f8jb8g.css';
import '../../css/q/qu4omacka.css';
import '../../css/k/kzr_fgbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rq7f8jb8g wm-k"/><path class="qu4omacka wm-k"/><path class="kzr_fgbah wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mehndi-hand-sketch" {...props}></Icon>
