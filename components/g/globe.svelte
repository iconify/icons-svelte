<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhda001sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="rhda001sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:globe" {...props}></Icon>
