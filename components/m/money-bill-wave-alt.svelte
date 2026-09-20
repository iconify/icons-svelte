<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbvbjvb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wbvbjvb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:money-bill-wave-alt" {...props}></Icon>
