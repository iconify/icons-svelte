<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jaqp_8b4j.css';
import '../../css/u/uvug2xw2n.css';
import '../../css/d/d-d0chbey.css';
import '../../css/v/v2qi7vbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="jaqp_8b4j"/><path clip-rule="evenodd" class="uvug2xw2n"/><path class="d-d0chbey"/><path class="v2qi7vbvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrow-solid-bracket-end" {...props}></Icon>
