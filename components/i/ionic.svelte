<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thpy47d_f.css';
import '../../css/e/e8x6debrh.css';
import '../../css/u/u96hv1wct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="thpy47d_f"><circle class="e8x6debrh"/><path class="u96hv1wct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ionic" {...props}></Icon>
