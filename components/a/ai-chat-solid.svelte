<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0u1j7bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0u1j7bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-chat-solid" {...props}></Icon>
