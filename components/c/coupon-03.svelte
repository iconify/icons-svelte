<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmmkl767k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmmkl767k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:coupon-03" {...props}></Icon>
