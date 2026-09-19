<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mwyb9cv3b.css';
import '../../css/w/w-0i0z5mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="mwyb9cv3b"/><rect class="w-0i0z5mu"/><rect class="mwyb9cv3b"/><rect class="w-0i0z5mu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:cloud-filled" {...props}></Icon>
