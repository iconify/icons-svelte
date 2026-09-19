<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tr6gbxluw.css';
import '../../css/k/knq1obbqm.css';
import '../../css/r/rlafmm9-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tr6gbxluw"/><path clip-rule="evenodd" class="knq1obbqm"/><path class="rlafmm9-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:battery-bolt" {...props}></Icon>
