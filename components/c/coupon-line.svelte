<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep2fcfbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep2fcfbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coupon-line" {...props}></Icon>
