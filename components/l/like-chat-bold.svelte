<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp3ta-1pq.css';
import '../../css/g/gfpj9w7rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp3ta-1pq"/><path class="gfpj9w7rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:like-chat-bold" {...props}></Icon>
