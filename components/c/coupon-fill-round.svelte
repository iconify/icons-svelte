<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7spb4buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7spb4buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:coupon-fill-round" {...props}></Icon>
