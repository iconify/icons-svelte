<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p5j-yozem.css';
import '../../css/h/h109fbbfv.css';
import '../../css/b/bwdsidbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p5j-yozem"/><path class="h109fbbfv"/><path class="bwdsidbcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:headphone-print" {...props}></Icon>
