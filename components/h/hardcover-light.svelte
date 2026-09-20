<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhpm9o8vk.css';
import '../../css/k/k4v90z5go.css';
import '../../css/h/h32mt3b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhpm9o8vk"/><path class="k4v90z5go"/><path class="h32mt3b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hardcover-light" {...props}></Icon>
