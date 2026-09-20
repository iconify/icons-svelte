<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqzmhm7-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uqzmhm7-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chat-status" {...props}></Icon>
