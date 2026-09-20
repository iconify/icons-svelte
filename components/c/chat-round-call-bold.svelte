<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lja_-7uem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lja_-7uem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-call-bold" {...props}></Icon>
