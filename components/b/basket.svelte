<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/g/g6-yw9fpp.css';
import '../../css/f/f0-5odbhv.css';
import '../../css/p/prkny4bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="g6-yw9fpp"/><path class="f0-5odbhv"/><path class="prkny4bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:basket" {...props}></Icon>
