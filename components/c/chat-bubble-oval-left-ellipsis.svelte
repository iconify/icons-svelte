<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1p_cwb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1p_cwb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chat-bubble-oval-left-ellipsis" {...props}></Icon>
