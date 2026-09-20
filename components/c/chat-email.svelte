<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpqfbubif.css';
import '../../css/m/m4dq5vbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cpqfbubif"/><path class="m4dq5vbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:chat-email" {...props}></Icon>
