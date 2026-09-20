<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khi6rrb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khi6rrb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-4-line" {...props}></Icon>
