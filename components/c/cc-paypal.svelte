<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjd_3-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xjd_3-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-paypal" {...props}></Icon>
