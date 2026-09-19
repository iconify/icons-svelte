<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phitpcbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phitpcbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-check-filled" {...props}></Icon>
