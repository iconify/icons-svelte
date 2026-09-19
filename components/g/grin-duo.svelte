<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/t/t99-pnb2y.css';
import '../../css/a/a8924ab8w.css';
import '../../css/o/o_xfh8bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="t99-pnb2y"/><path class="a8924ab8w"/><path class="o_xfh8bmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-duo" {...props}></Icon>
