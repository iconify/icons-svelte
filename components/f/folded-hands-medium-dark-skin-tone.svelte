<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zym40bb_i.css';
import '../../css/h/h7_1mrqjr.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/u/u9ce-33wr.css';
import '../../css/h/h0--35b1u.css';
import '../../css/f/fordnus3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zym40bb_i"/><path class="h7_1mrqjr"/><g class="ij2x_72vy"><path class="u9ce-33wr"/><path class="h0--35b1u"/><path class="fordnus3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:folded-hands-medium-dark-skin-tone" {...props}></Icon>
