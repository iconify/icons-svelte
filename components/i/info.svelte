<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vo03lkbbh.css';
import '../../css/j/jbw52u0nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><ellipse class="vo03lkbbh"/><path class="jbw52u0nv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:info" {...props}></Icon>
