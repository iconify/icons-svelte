<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ty2npnbqw.css';
import '../../css/g/gkeer5b_h.css';
import '../../css/b/bk4lkpblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ty2npnbqw"/><path class="gkeer5b_h"/><path class="bk4lkpblv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:building-1-duo" {...props}></Icon>
