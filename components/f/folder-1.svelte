<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s0vxb8b6n.css';
import '../../css/z/z8ia2hcik.css';
import '../../css/q/qj7vtlbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="s0vxb8b6n"/><path class="z8ia2hcik"/><path clip-rule="evenodd" class="qj7vtlbpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:folder-1" {...props}></Icon>
