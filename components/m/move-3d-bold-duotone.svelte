<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cc5sghbks.css';
import '../../css/q/qr17esspr.css';
import '../../css/p/pj6r6abuc.css';
import '../../css/c/cyvlt_bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cc5sghbks"/><path class="qr17esspr"/><path class="pj6r6abuc"/><path class="cyvlt_bvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-3d-bold-duotone" {...props}></Icon>
