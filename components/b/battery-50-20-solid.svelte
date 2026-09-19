<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e4l7b9bzv.css';
import '../../css/o/ox011_f-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="e4l7b9bzv"/><path clip-rule="evenodd" class="ox011_f-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-50-20-solid" {...props}></Icon>
