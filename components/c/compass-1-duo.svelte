<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z7qxbnbvo.css';
import '../../css/d/dol-jyfgm.css';
import '../../css/k/k3cj--b3l.css';
import '../../css/g/g0_mboyku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z7qxbnbvo"/><path class="dol-jyfgm"/><path class="k3cj--b3l"/><path class="g0_mboyku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:compass-1-duo" {...props}></Icon>
