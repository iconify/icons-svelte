<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9fzjpvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bw9fzjpvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:chat-typing-alt-outline" {...props}></Icon>
