<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtykxymon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qtykxymon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-left" {...props}></Icon>
