<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wjvia45sw.css';
import '../../css/t/tm8p9gwlr.css';
import '../../css/p/p8eiskbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wjvia45sw"/><path class="tm8p9gwlr"/><path class="p8eiskbvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:gift-1" {...props}></Icon>
