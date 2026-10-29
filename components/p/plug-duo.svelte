<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f912b9wmg.css';
import '../../css/c/cgczxwbbg.css';
import '../../css/h/hqgq3dbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f912b9wmg"/><path class="cgczxwbbg wm-a"/><path class="hqgq3dbge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plug-duo" {...props}></Icon>
