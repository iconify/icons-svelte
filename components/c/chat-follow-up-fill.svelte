<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgun1xb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgun1xb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-follow-up-fill" {...props}></Icon>
