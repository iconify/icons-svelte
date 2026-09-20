<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9p1ohbtx.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/l/l0cxmccps.css';
import '../../css/v/vpf4mac0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h9p1ohbtx"/><g class="mc2zb0bvp"><path class="l0cxmccps"/><path class="vpf4mac0n"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-bold-duotone" {...props}></Icon>
