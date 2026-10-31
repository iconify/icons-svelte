<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6kv9-b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6kv9-b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-close-round" {...props}></Icon>
