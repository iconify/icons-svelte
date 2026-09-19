<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hc654n61t.css';
import '../../css/g/g0l4wt5qi.css';
import '../../css/t/txtwnjbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="hc654n61t"/><path clip-rule="evenodd" class="g0l4wt5qi"/><path class="txtwnjbdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laptop-cog-bold" {...props}></Icon>
