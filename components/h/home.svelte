<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/azlmfgbpz.css';
import '../../css/v/vu-t8mz1s.css';
import '../../css/b/bx2-xs7ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="azlmfgbpz"/><path class="vu-t8mz1s"/><path class="bx2-xs7ey wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:home" {...props}></Icon>
