<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usv4oibvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usv4oibvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-remove" {...props}></Icon>
