<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m23wa8bmm.css';
import '../../css/l/luchi18gl.css';
import '../../css/u/u18d3ddyr.css';
import '../../css/p/pqg7pcb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m23wa8bmm"/><path class="luchi18gl"/><path class="u18d3ddyr"/><path class="pqg7pcb_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:clock-1-outline" {...props}></Icon>
