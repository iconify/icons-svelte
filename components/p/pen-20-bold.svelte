<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg2rt9b6k.css';
import '../../css/i/i7oy_ep3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cg2rt9b6k"/><path class="i7oy_ep3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pen-20-bold" {...props}></Icon>
