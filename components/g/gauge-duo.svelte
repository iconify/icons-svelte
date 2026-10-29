<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vikq7_blh.css';
import '../../css/f/f4wn345na.css';
import '../../css/f/fq34ly3dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vikq7_blh"/><path class="f4wn345na wm-a"/><path class="fq34ly3dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gauge-duo" {...props}></Icon>
