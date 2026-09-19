<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vmnknnmuy.css';
import '../../css/p/pg98zb21c.css';
import '../../css/i/imszhdckf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="vmnknnmuy"/><path class="pg98zb21c"/><path class="imszhdckf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bells-bold" {...props}></Icon>
