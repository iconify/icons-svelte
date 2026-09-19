<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g85xu4buw.css';
import '../../css/p/p0a0ftcxr.css';
import '../../css/l/lyvx4mbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="g85xu4buw"/><path clip-rule="evenodd" class="p0a0ftcxr"/><path class="lyvx4mbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-100-bold" {...props}></Icon>
