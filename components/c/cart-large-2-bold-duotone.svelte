<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lphr8070y.css';
import '../../css/p/p-86ddbul.css';
import '../../css/x/xnvx4ncsb.css';
import '../../css/w/wf4hdghvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lphr8070y"/><path class="p-86ddbul"/><path class="xnvx4ncsb"/><path class="wf4hdghvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-2-bold-duotone" {...props}></Icon>
