<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ul3wxg7ca.css';
import '../../css/p/p5853ld8s.css';
import '../../css/a/a7vsmybvj.css';
import '../../css/w/w0onx4o4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":500};
const content = `<g class="bi12bsetm"><path class="ul3wxg7ca"/><path class="p5853ld8s"/><path class="a7vsmybvj"/><path class="w0onx4o4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:passport-js" {...props}></Icon>
