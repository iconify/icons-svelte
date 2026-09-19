<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hxlk_nblr.css';
import '../../css/x/x1a5cg2bq.css';
import '../../css/w/wlgmf7bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hxlk_nblr"/><path class="x1a5cg2bq"/><path class="wlgmf7bsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-slash-duo" {...props}></Icon>
