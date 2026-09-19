<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvds6zbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pvds6zbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-fill" {...props}></Icon>
