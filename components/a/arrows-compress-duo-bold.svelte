<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bwc47kb7e.css';
import '../../css/h/hqpee5bzp.css';
import '../../css/g/gx2ftuxqj.css';
import '../../css/q/q8g393bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="bwc47kb7e"/><path class="hqpee5bzp"/><path class="gx2ftuxqj"/><path class="q8g393bjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-compress-duo-bold" {...props}></Icon>
