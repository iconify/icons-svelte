<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/db9oi35bt.css';
import '../../css/l/le9c2_xok.css';
import '../../css/v/v-x-g53_a.css';
import '../../css/w/w7xw-2bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="db9oi35bt wm-deco"/><path class="le9c2_xok wm-k"/><path class="v-x-g53_a wm-k"/><path class="w7xw-2bff wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:piggy-bank-blueprint" {...props}></Icon>
