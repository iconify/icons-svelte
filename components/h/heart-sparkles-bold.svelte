<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uhb779nue.css';
import '../../css/g/g9wzcsquv.css';
import '../../css/b/bcsqw5n-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="uhb779nue"/><path clip-rule="evenodd" class="g9wzcsquv"/><path class="bcsqw5n-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-sparkles-bold" {...props}></Icon>
