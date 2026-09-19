<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yn-gg53du.css';
import '../../css/h/h_4u6m5ma.css';
import '../../css/f/f2x5c8oex.css';
import '../../css/c/ct5sofbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="yn-gg53du"/><path clip-rule="evenodd" class="h_4u6m5ma"/><path class="f2x5c8oex"/><path class="ct5sofbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:exposure" {...props}></Icon>
