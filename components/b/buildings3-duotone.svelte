<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w72fq3cev.css';
import '../../css/g/g_6c7be5d.css';
import '../../css/m/m9-0_tbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w72fq3cev"/><path class="g_6c7be5d"/><path class="m9-0_tbam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buildings3-duotone" {...props}></Icon>
