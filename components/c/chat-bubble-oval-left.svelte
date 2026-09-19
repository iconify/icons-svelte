<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev91xjb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev91xjb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chat-bubble-oval-left" {...props}></Icon>
