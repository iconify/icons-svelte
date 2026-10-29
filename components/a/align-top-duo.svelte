<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oy6gsz-qj.css';
import '../../css/w/wj05nbxlz.css';
import '../../css/g/g4o146b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="oy6gsz-qj wm-a"/><path class="wj05nbxlz"/><path class="g4o146b6z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-top-duo" {...props}></Icon>
