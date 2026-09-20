<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz0usb8zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz0usb8zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:openai-logo" {...props}></Icon>
