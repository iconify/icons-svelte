<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vlx_mbcyg.css';
import '../../css/h/h103ytq6b.css';
import '../../css/b/bvmd-ab7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vlx_mbcyg"/><path class="h103ytq6b"/><path class="bvmd-ab7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:credit-card-duo" {...props}></Icon>
