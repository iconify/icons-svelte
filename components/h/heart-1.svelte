<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i513c3bdm.css';
import '../../css/l/l7pnvrook.css';
import '../../css/h/hjuzicb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="i513c3bdm"/><path class="l7pnvrook"/><path class="hjuzicb2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:heart-1" {...props}></Icon>
