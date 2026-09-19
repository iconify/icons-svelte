<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/r1zv4vbmm.css';
import '../../css/r/rsjsrjd2a.css';
import '../../css/l/lwa-rvbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="r1zv4vbmm"/><path class="rsjsrjd2a"/><path class="lwa-rvbps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:neutral-face-thin" {...props}></Icon>
