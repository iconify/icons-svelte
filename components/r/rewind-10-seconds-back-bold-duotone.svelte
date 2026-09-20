<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/ds0znlb8s.css';
import '../../css/t/tljv-xepv.css';
import '../../css/u/ufb_r8e8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ds0znlb8s"/><path clip-rule="evenodd" class="tljv-xepv"/><path clip-rule="evenodd" class="ufb_r8e8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-10-seconds-back-bold-duotone" {...props}></Icon>
