<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r0ro9ykyt.css';
import '../../css/w/w_l8fwasu.css';
import '../../css/h/haf-s8w2i.css';
import '../../css/t/t48_nabfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="r0ro9ykyt"/><path class="w_l8fwasu"/><path class="haf-s8w2i"/><path class="t48_nabfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mailbox-duo" {...props}></Icon>
