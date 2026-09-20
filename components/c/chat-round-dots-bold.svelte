<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz80frbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz80frbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-dots-bold" {...props}></Icon>
