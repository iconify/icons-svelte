<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mgteurj5l.css';
import '../../css/h/hupbp2dcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<g class="n1lsf0bnc"><path class="mgteurj5l"/><path class="hupbp2dcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:moon-star" {...props}></Icon>
