<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ie49pn7lv.css';
import '../../css/r/rlafmm9-k.css';
import '../../css/g/guqiiex5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ie49pn7lv"/><path class="rlafmm9-k"/><path clip-rule="evenodd" class="guqiiex5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:battery-1" {...props}></Icon>
