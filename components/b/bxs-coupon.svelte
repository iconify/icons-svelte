<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_lny9fez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_lny9fez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-coupon" {...props}></Icon>
