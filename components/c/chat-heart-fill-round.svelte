<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inhk1yb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inhk1yb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-heart-fill-round" {...props}></Icon>
