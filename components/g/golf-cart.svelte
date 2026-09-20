<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3bltac4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t3bltac4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:golf-cart" {...props}></Icon>
