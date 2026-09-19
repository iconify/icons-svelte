<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l6isbtbxr.css';
import '../../css/a/a47_f0m3e.css';
import '../../css/c/cx_isemhf.css';
import '../../css/d/ddq-3fb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l6isbtbxr"/><path class="a47_f0m3e"/><path class="cx_isemhf"/><path class="ddq-3fb3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-circle-outline" {...props}></Icon>
