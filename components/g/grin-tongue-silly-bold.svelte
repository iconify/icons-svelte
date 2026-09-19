<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e4lzz6btz.css';
import '../../css/y/yfft0bc1h.css';
import '../../css/m/mmom_acqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="e4lzz6btz"/><path clip-rule="evenodd" class="yfft0bc1h"/><path clip-rule="evenodd" class="mmom_acqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-tongue-silly-bold" {...props}></Icon>
