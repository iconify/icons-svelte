<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m3duksq9k.css';
import '../../css/p/pmv50n_jk.css';
import '../../css/f/fbnjgqhbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m3duksq9k"/><path class="pmv50n_jk"/><path class="fbnjgqhbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:download" {...props}></Icon>
