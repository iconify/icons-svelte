<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/o/osadutb4f.css';
import '../../css/c/cs3-aebaf.css';
import '../../css/v/vmg2ow2hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="osadutb4f"/><rect class="cs3-aebaf"/><rect class="vmg2ow2hl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layout-1-bold" {...props}></Icon>
