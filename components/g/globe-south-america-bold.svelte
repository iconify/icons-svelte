<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lfdnlqvyw.css';
import '../../css/q/qb0mibb1e.css';
import '../../css/w/w4ipckadh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lfdnlqvyw"/><path clip-rule="evenodd" class="qb0mibb1e"/><path class="w4ipckadh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-south-america-bold" {...props}></Icon>
