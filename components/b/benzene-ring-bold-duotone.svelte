<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fs1s4bb3o.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/f/f5f0jwb-w.css';
import '../../css/g/gqdhlkbho.css';
import '../../css/d/d8_onbakg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fs1s4bb3o"/><g class="mc2zb0bvp"><path class="f5f0jwb-w"/><path class="gqdhlkbho"/><path class="d8_onbakg"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:benzene-ring-bold-duotone" {...props}></Icon>
