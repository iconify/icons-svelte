<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iti7hsb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iti7hsb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:programming-user-chat-bold" {...props}></Icon>
