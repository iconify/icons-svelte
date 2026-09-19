<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z67_wkbeg.css';
import '../../css/s/snjledccd.css';
import '../../css/e/eu31d_bii.css';
import '../../css/t/tybfplb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z67_wkbeg"/><path class="snjledccd"/><path class="eu31d_bii"/><path class="tybfplb3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-atlas-duo" {...props}></Icon>
