<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xar3zbcoy.css';
import '../../css/q/qbj1zqrnu.css';
import '../../css/o/omt0vob3d.css';
import '../../css/p/pl37d4g4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xar3zbcoy"/><path class="qbj1zqrnu"/><path class="omt0vob3d"/><path class="pl37d4g4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-sleep-bold-duotone" {...props}></Icon>
