<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/m/m9569c2lu.css';
import '../../css/p/pfmce6b4y.css';
import '../../css/n/n40ywwckf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><rect class="m9569c2lu"/><rect class="pfmce6b4y"/><rect class="n40ywwckf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-layout-2-bold" {...props}></Icon>
