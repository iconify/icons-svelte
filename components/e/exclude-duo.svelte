<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t446ypbya.css';
import '../../css/r/rso6jlb3w.css';
import '../../css/f/fslmcjxus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t446ypbya"/><path class="rso6jlb3w"/><path class="fslmcjxus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclude-duo" {...props}></Icon>
