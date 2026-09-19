<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nlbukzbvh.css';
import '../../css/n/nsvaqzcrz.css';
import '../../css/e/enxj31s0p.css';
import '../../css/b/bgasabkle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="nlbukzbvh"/><path class="nsvaqzcrz"/><path class="enxj31s0p"/><path clip-rule="evenodd" class="bgasabkle"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-slash-bold" {...props}></Icon>
