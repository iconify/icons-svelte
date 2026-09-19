<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6a4tubxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r6a4tubxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-right-text-fill" {...props}></Icon>
