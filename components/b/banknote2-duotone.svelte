<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yfsl5absb.css';
import '../../css/k/k11donbcg.css';
import '../../css/w/wl3zckjly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yfsl5absb"/><path clip-rule="evenodd" class="k11donbcg"/><path class="wl3zckjly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:banknote2-duotone" {...props}></Icon>
