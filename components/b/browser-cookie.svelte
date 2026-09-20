<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hl-yb4s0v.css';
import '../../css/g/g4pqkcclt.css';
import '../../css/r/rfjwc7d-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hl-yb4s0v"/><path clip-rule="evenodd" class="g4pqkcclt"/><path class="rfjwc7d-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:browser-cookie" {...props}></Icon>
