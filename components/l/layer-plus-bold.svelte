<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pg80exb6e.css';
import '../../css/w/w7-178bnk.css';
import '../../css/k/k2-hmwbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pg80exb6e"/><path class="w7-178bnk"/><path class="k2-hmwbsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layer-plus-bold" {...props}></Icon>
