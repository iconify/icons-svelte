<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ub4u4kwda.css';
import '../../css/y/ys-_x32cm.css';
import '../../css/o/o6vihjm2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ub4u4kwda"/><path class="ys-_x32cm"/><path class="o6vihjm2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:curtains" {...props}></Icon>
