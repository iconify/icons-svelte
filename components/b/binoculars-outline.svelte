<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p0w9xzp5p.css';
import '../../css/x/xbu3phb9u.css';
import '../../css/p/pfslbpo-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="p0w9xzp5p"/><path class="xbu3phb9u"/><path class="pfslbpo-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:binoculars-outline" {...props}></Icon>
