<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sssfo6btx.css';
import '../../css/p/p4nrc_jlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sssfo6btx"/><path class="p4nrc_jlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupon-20-bold" {...props}></Icon>
