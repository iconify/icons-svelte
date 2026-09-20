<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pb65vs_ab.css';
import '../../css/r/rn08x5brb.css';
import '../../css/k/kcy73erti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pb65vs_ab"/><path class="rn08x5brb"/><path class="kcy73erti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bomb-bold" {...props}></Icon>
