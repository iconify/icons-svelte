<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb-3c9yjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-3c9yjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cart-x" {...props}></Icon>
