<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x29xhpcfs.css';
import '../../css/e/e5hrx7bil.css';
import '../../css/u/uccg2r8dc.css';
import '../../css/q/qff5zwbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x29xhpcfs"/><path class="e5hrx7bil"/><path class="uccg2r8dc"/><path class="qff5zwbcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-square-outline" {...props}></Icon>
