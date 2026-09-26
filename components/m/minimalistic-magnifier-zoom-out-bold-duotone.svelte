<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r0xhknb7f.css';
import '../../css/y/yz0ujqbim.css';
import '../../css/t/tu8a1hb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="r0xhknb7f"/><path class="yz0ujqbim"/><path class="tu8a1hb1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-zoom-out-bold-duotone" {...props}></Icon>
