<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dtubnabwv.css';
import '../../css/d/dhewf6b3g.css';
import '../../css/n/nxd3_8gtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="dtubnabwv"/><path class="dhewf6b3g"/><path clip-rule="evenodd" class="nxd3_8gtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-1-slash-bold" {...props}></Icon>
