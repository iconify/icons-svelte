<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k5c7wwyuh.css';
import '../../css/d/dbxivir6k.css';
import '../../css/x/xcez03_th.css';
import '../../css/j/jjivkrbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k5c7wwyuh"/><path class="dbxivir6k wm-a"/><path class="wm-a xcez03_th"/><path class="jjivkrbpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cricket-duo" {...props}></Icon>
