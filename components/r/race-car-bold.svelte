<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/ve3z1lb2g.css';
import '../../css/l/lxg7su77s.css';
import '../../css/p/p3mukqotj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ve3z1lb2g"/><path clip-rule="evenodd" class="lxg7su77s"/><path class="p3mukqotj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:race-car-bold" {...props}></Icon>
