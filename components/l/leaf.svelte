<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g5qhxlbsq.css';
import '../../css/z/z2t0oq1-o.css';
import '../../css/f/f1ueyq9sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="g5qhxlbsq"/><path class="z2t0oq1-o"/><path class="f1ueyq9sn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:leaf" {...props}></Icon>
