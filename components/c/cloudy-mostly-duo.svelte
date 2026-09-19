<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rnk91y7oh.css';
import '../../css/l/lzqwbvb5e.css';
import '../../css/q/qoly2l_kl.css';
import '../../css/p/p9b9gbb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rnk91y7oh"/><path class="lzqwbvb5e"/><path class="qoly2l_kl"/><path class="p9b9gbb7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloudy-mostly-duo" {...props}></Icon>
