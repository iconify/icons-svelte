<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/az-3uob_u.css';
import '../../css/y/y-v_cw-sh.css';
import '../../css/n/n3_y8obgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="az-3uob_u"/><path class="y-v_cw-sh"/><path class="n3_y8obgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightbulb-1-bold" {...props}></Icon>
