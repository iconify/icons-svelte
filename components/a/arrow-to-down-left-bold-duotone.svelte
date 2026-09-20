<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r5723789x.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/u/ucxixg8jo.css';
import '../../css/r/rl4sfbcqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r5723789x"/><g class="mc2zb0bvp"><path class="ucxixg8jo"/><path class="rl4sfbcqv"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-left-bold-duotone" {...props}></Icon>
