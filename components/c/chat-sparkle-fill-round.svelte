<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci9iid05n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci9iid05n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-sparkle-fill-round" {...props}></Icon>
