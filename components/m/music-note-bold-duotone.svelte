<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dkdkhr53o.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/t/t-oeigerl.css';
import '../../css/k/khxz2ebum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dkdkhr53o"/><g class="mc2zb0bvp"><path class="t-oeigerl"/><path class="khxz2ebum"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-bold-duotone" {...props}></Icon>
