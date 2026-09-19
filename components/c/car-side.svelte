<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b6ihv4k4v.css';
import '../../css/g/gqi_w2iyl.css';
import '../../css/j/jz3df6bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="b6ihv4k4v"/><path clip-rule="evenodd" class="gqi_w2iyl"/><path class="jz3df6bjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:car-side" {...props}></Icon>
