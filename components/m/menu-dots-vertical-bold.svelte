<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/raucetsey.css';
import '../../css/u/uor89vbsf.css';
import '../../css/z/zeiub32xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="raucetsey"/><path class="uor89vbsf"/><path class="zeiub32xo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-vertical-bold" {...props}></Icon>
