<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt41hsqgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt41hsqgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-filled" {...props}></Icon>
