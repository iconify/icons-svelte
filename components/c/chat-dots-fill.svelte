<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg-0k0bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jg-0k0bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-dots-fill" {...props}></Icon>
