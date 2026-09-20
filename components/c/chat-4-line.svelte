<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voookubxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voookubxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-4-line" {...props}></Icon>
