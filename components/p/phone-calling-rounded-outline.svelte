<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ap2wj3w6d.css';
import '../../css/b/bimm2xbjr.css';
import '../../css/f/fnflbekrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ap2wj3w6d"/><path clip-rule="evenodd" class="bimm2xbjr"/><path clip-rule="evenodd" class="fnflbekrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-rounded-outline" {...props}></Icon>
