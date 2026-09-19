<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r8xajdb2x.css';
import '../../css/u/u5sun390o.css';
import '../../css/a/aqg1apivn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="r8xajdb2x"/><path class="u5sun390o"/><path class="aqg1apivn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:file-duo" {...props}></Icon>
