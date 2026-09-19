<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/smgzgcbpq.css';
import '../../css/j/jt1js_paa.css';
import '../../css/s/sk8-i7dpz.css';
import '../../css/j/js6g9scdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="smgzgcbpq"/><path class="jt1js_paa"/><path clip-rule="evenodd" class="sk8-i7dpz"/><path class="js6g9scdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:quote-bold" {...props}></Icon>
