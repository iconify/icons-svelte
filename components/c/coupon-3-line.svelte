<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti44f9bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti44f9bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coupon-3-line" {...props}></Icon>
