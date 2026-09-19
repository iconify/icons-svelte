<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/v/v98yaftnr.css';
import '../../css/w/wyzcj9bru.css';
import '../../css/y/yp56kod4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="v98yaftnr"/><path class="wyzcj9bru"/><path class="yp56kod4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:binoculars" {...props}></Icon>
