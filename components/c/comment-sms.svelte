<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6z99bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yd6z99bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comment-sms" {...props}></Icon>
