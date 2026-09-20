<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvpz8ohbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvpz8ohbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-delete-fill" {...props}></Icon>
