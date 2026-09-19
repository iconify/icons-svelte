<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi3-nmwyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi3-nmwyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-cancel-filled" {...props}></Icon>
