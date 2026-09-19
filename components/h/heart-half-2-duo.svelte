<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ncjytp73c.css';
import '../../css/z/z5waj9zlf.css';
import '../../css/z/zmkdzsyhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ncjytp73c"/><path class="z5waj9zlf"/><path class="zmkdzsyhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half-2-duo" {...props}></Icon>
