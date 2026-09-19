<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h2d8ur0oc.css';
import '../../css/l/ldbhdeycv.css';
import '../../css/w/w1uol0bxe.css';
import '../../css/y/y-vrt5a7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="h2d8ur0oc"/><path clip-rule="evenodd" class="ldbhdeycv"/><path class="w1uol0bxe"/><path class="y-vrt5a7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:car-side-bold" {...props}></Icon>
