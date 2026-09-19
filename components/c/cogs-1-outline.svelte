<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zx7uv5q7n.css';
import '../../css/f/f_mfzu3uv.css';
import '../../css/y/yu-13qbwi.css';
import '../../css/g/gablpk-so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zx7uv5q7n"/><path class="f_mfzu3uv"/><path class="yu-13qbwi"/><path class="gablpk-so"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogs-1-outline" {...props}></Icon>
