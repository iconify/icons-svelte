<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zagh264zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zagh264zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-settings-fill" {...props}></Icon>
