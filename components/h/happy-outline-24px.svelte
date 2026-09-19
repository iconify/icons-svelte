<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rl0p0lbfb.css';
import '../../css/q/q_2xdtkfh.css';
import '../../css/z/zso2mq8uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rl0p0lbfb"/><path clip-rule="evenodd" class="q_2xdtkfh"/><path clip-rule="evenodd" class="zso2mq8uq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:happy-outline-24px" {...props}></Icon>
