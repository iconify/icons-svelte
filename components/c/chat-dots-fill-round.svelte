<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g83pymb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g83pymb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-dots-fill-round" {...props}></Icon>
