<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl41xxbat.css';
import '../../css/a/a8eh2dnic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tl41xxbat"/><path class="a8eh2dnic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupon-20" {...props}></Icon>
