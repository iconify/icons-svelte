<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfq4xub6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfq4xub6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-text-filled" {...props}></Icon>
