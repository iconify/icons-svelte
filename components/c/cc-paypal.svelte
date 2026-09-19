<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn32y0v_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vn32y0v_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cc-paypal" {...props}></Icon>
