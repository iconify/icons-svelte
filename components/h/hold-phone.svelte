<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xnkn0ubcl.css';
import '../../css/k/k315r8bxr.css';
import '../../css/c/cpb1ribrk.css';
import '../../css/v/v-zfuob0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="xnkn0ubcl"/><path class="k315r8bxr"/><path class="cpb1ribrk"/><path class="v-zfuob0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hold-phone" {...props}></Icon>
