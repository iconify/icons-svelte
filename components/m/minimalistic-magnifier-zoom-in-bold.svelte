<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yz0ujqbim.css';
import '../../css/s/s613mrand.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yz0ujqbim"/><path clip-rule="evenodd" class="s613mrand"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-zoom-in-bold" {...props}></Icon>
