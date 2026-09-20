<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4wz7200e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4wz7200e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coupon-2-fill" {...props}></Icon>
