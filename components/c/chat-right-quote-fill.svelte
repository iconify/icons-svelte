<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgc4r4n1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vgc4r4n1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-right-quote-fill" {...props}></Icon>
