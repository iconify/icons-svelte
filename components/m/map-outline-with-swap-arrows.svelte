<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw7e6_c3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dw7e6_c3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-outline-with-swap-arrows" {...props}></Icon>
