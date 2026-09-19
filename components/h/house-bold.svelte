<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vx92c-bsp.css';
import '../../css/z/z6hdjobbr.css';
import '../../css/g/ghfvu9bvy.css';
import '../../css/i/ic6_0vbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vx92c-bsp"/><path class="z6hdjobbr"/><path clip-rule="evenodd" class="ghfvu9bvy"/><path class="ic6_0vbog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-bold" {...props}></Icon>
