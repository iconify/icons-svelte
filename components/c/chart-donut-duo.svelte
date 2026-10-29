<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ugfrr8bnj.css';
import '../../css/z/zo12m9vrh.css';
import '../../css/u/uv6uwdbji.css';
import '../../css/v/v1055zads.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ugfrr8bnj"/><path class="wm-a zo12m9vrh"/><path class="uv6uwdbji wm-a"/><path class="v1055zads"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-donut-duo" {...props}></Icon>
