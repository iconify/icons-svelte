<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h2r9s7v-s.css';
import '../../css/r/rpxk0yble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="h2r9s7v-s"/><path clip-rule="evenodd" class="rpxk0yble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pharmacy-1-bold" {...props}></Icon>
