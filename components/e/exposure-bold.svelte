<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nyj1zdbps.css';
import '../../css/d/do94kcirf.css';
import '../../css/m/mvqn6zbzw.css';
import '../../css/z/zc_5uebyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="nyj1zdbps"/><path class="do94kcirf"/><path class="mvqn6zbzw"/><path class="zc_5uebyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exposure-bold" {...props}></Icon>
