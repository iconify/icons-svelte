<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi1222_ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bi1222_ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:product-management" {...props}></Icon>
