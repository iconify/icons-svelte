<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j0lvivb4x.css';
import '../../css/m/me-irab7m.css';
import '../../css/f/f_rhc-bwk.css';
import '../../css/m/m-i1l3b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j0lvivb4x"/><path class="me-irab7m"/><path class="f_rhc-bwk"/><path class="m-i1l3b8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrows-expand-duo" {...props}></Icon>
