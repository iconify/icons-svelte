<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j3_4id34h.css';
import '../../css/g/gd92vsrsz.css';
import '../../css/r/rq8v8obdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="j3_4id34h"/><path clip-rule="evenodd" class="gd92vsrsz"/><path class="rq8v8obdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:images-bold" {...props}></Icon>
