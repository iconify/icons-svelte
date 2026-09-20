<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y96e-6bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y96e-6bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:coupon-outline" {...props}></Icon>
