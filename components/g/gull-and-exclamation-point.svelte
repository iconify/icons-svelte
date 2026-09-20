<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsovqt3vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tsovqt3vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gull-and-exclamation-point" {...props}></Icon>
