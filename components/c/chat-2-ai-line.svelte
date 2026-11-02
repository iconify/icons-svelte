<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkz182ngp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkz182ngp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-2-ai-line" {...props}></Icon>
