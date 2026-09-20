<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hiqwxob7b.css';
import '../../css/u/uxddagbff.css';
import '../../css/p/p-tl4pbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hiqwxob7b"/><path class="uxddagbff"/><path class="p-tl4pbfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-graph-bold-duotone" {...props}></Icon>
