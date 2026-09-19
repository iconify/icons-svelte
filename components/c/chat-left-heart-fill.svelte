<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl3hfwebj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xl3hfwebj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-left-heart-fill" {...props}></Icon>
