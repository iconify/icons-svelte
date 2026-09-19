<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e76ndrbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":400};
const content = `<path class="e76ndrbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-wifi" {...props}></Icon>
