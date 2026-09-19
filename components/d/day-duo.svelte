<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b80p1rbvv.css';
import '../../css/m/momohwbsb.css';
import '../../css/q/qr3zbyjzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b80p1rbvv"/><path class="momohwbsb"/><path class="qr3zbyjzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:day-duo" {...props}></Icon>
