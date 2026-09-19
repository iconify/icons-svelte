<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f12n77b0y.css';
import '../../css/i/igl--8b1c.css';
import '../../css/g/g63pph37i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f12n77b0y"/><path class="igl--8b1c"/><path class="g63pph37i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:elevator-duo" {...props}></Icon>
