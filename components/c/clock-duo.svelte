<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gtww1vtox.css';
import '../../css/g/gi50h7bfm.css';
import '../../css/t/t5ceytyal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gtww1vtox"/><path class="gi50h7bfm"/><path class="t5ceytyal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:clock-duo" {...props}></Icon>
