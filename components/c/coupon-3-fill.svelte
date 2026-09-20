<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsvrzestq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsvrzestq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coupon-3-fill" {...props}></Icon>
