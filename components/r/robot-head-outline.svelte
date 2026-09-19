<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jz4qbpbes.css';
import '../../css/o/otbkqlb6h.css';
import '../../css/h/hxogdab1a.css';
import '../../css/k/kayfskbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jz4qbpbes"/><path class="otbkqlb6h"/><path class="hxogdab1a"/><path class="kayfskbga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:robot-head-outline" {...props}></Icon>
