<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ck1931bjh.css';
import '../../css/r/r-0ieohmi.css';
import '../../css/q/q1pokukeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ck1931bjh"/><path class="r-0ieohmi"/><path class="q1pokukeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:heart-half-2" {...props}></Icon>
