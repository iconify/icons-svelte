<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eja77yp7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eja77yp7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gateway-parallel" {...props}></Icon>
