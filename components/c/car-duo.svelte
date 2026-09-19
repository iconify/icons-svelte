<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q7nk9kbbt.css';
import '../../css/l/lu2cild_d.css';
import '../../css/h/hemvncbmx.css';
import '../../css/h/hqycppbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="q7nk9kbbt"/><path class="lu2cild_d"/><path class="hemvncbmx"/><path class="hqycppbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:car-duo" {...props}></Icon>
