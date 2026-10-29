<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wht_zowdm.css';
import '../../css/z/zm38tmb2p.css';
import '../../css/b/buxga7syi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wht_zowdm"/><path class="wm-a zm38tmb2p"/><path class="buxga7syi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:passport-duo" {...props}></Icon>
