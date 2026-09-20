<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5512bc7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="m5512bc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-sleet" {...props}></Icon>
