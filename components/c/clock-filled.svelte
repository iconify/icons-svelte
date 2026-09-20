<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc5ee2brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yc5ee2brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:clock-filled" {...props}></Icon>
