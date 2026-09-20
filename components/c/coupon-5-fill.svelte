<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz9_n9bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz9_n9bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coupon-5-fill" {...props}></Icon>
