<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/ktd21acbt.css';
import '../../css/o/o14py5b7r.css';
import '../../css/f/fl2utnblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ktd21acbt"/><path class="o14py5b7r"/><path class="fl2utnblk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bookmarks-duo" {...props}></Icon>
