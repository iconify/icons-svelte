<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bt--9eb0w.css';
import '../../css/h/hqgq3dbge.css';
import '../../css/h/hpi0ccblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bt--9eb0w wm-a"/><path class="hqgq3dbge"/><path class="hpi0ccblh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plug" {...props}></Icon>
