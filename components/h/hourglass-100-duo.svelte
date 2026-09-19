<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/td8-cml1e.css';
import '../../css/s/szy8jkqkv.css';
import '../../css/t/te7ffcutq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="td8-cml1e"/><path class="szy8jkqkv"/><path class="te7ffcutq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-100-duo" {...props}></Icon>
