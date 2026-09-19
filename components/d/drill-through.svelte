<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7-k3vx_v.css';
import '../../css/i/i-hdiybge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p7-k3vx_v"/><path class="i-hdiybge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drill-through" {...props}></Icon>
