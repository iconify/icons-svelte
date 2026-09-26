<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/q/qlhqa5a1y.css';
import '../../css/s/svu3l535p.css';
import '../../css/u/ub62qzant.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="qlhqa5a1y"/><path class="svu3l535p"/></g><path clip-rule="evenodd" class="ub62qzant"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-bold-duotone" {...props}></Icon>
