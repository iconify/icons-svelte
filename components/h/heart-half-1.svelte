<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ck1931bjh.css';
import '../../css/q/qfd3apbyf.css';
import '../../css/d/det13e0ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ck1931bjh"/><path class="qfd3apbyf"/><path class="det13e0ij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:heart-half-1" {...props}></Icon>
