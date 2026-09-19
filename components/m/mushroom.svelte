<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e-x8ftsqu.css';
import '../../css/q/qxwe76bwh.css';
import '../../css/k/kyfprmvqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="e-x8ftsqu"/><path class="qxwe76bwh"/><path clip-rule="evenodd" class="kyfprmvqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:mushroom" {...props}></Icon>
