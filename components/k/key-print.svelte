<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vgq9s-_5c.css';
import '../../css/k/kg6whmtsp.css';
import '../../css/x/x_c_7bkus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="vgq9s-_5c"/><path clip-rule="evenodd" class="kg6whmtsp"/><path clip-rule="evenodd" class="x_c_7bkus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:key-print" {...props}></Icon>
