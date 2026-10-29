<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rpsv5dbfy.css';
import '../../css/n/ngj96acjh.css';
import '../../css/z/z31jlbbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rpsv5dbfy"/><path class="ngj96acjh wm-a"/><path class="z31jlbbvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:factory-duo" {...props}></Icon>
