<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/ed79v0bnq.css';
import '../../css/o/otkj6bm5u.css';
import '../../css/r/r5o5b2bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g transform="translate(0 1)" class="n1lsf0bnc"><ellipse class="ed79v0bnq"/><path class="otkj6bm5u"/><path class="r5o5b2bfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:airplane-2" {...props}></Icon>
