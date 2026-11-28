<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/l/lhi-d6nau.css';
import '../../css/s/sd-bzfbly.css';
import '../../css/e/emidn4bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ud95brdct"/><path class="lhi-d6nau"/><path class="sd-bzfbly"/><path class="emidn4bkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-donut" {...props}></Icon>
