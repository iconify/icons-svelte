<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se67ui62b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se67ui62b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-close-bold" {...props}></Icon>
