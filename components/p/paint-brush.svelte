<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eu560-7oy.css';
import '../../css/z/z0nhkbcvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eu560-7oy"/><path class="z0nhkbcvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:paint-brush" {...props}></Icon>
