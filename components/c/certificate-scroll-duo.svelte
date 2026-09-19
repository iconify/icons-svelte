<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t2qlxabla.css';
import '../../css/t/tjzpjrtvc.css';
import '../../css/l/lek275ekg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t2qlxabla"/><path class="tjzpjrtvc"/><path class="lek275ekg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:certificate-scroll-duo" {...props}></Icon>
