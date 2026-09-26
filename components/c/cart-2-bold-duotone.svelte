<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/m/me44qacwj.css';
import '../../css/f/fpb37bc7d.css';
import '../../css/o/o21lzzbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="me44qacwj"/><path class="fpb37bc7d"/></g><path clip-rule="evenodd" class="o21lzzbdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-2-bold-duotone" {...props}></Icon>
