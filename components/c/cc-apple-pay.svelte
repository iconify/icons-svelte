<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp4ber88j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zp4ber88j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-apple-pay" {...props}></Icon>
