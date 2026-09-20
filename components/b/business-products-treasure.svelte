<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hamk2lbll.css';
import '../../css/v/vnai25b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hamk2lbll"/><path class="vnai25b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-treasure" {...props}></Icon>
