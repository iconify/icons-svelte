<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pittov07q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pittov07q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:bubble-chat-2" {...props}></Icon>
