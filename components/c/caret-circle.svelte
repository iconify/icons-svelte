<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pcb8zqbpp.css';
import '../../css/u/uudf2r-ks.css';
import '../../css/d/dukave61f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pcb8zqbpp"/><path class="uudf2r-ks"/><path class="dukave61f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:caret-circle" {...props}></Icon>
