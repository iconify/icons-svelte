<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7i07eb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7i07eb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coupon-fill" {...props}></Icon>
