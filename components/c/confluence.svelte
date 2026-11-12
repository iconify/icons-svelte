<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nlsrcd06b.css';
import '../../css/d/didnbvtvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":75,"height":75};
const content = `<g class="ft5dv1b6b"><path class="nlsrcd06b"/><path class="didnbvtvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:confluence" {...props}></Icon>
