<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf5p35bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vf5p35bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-oval-left-ellipsis-16-solid" {...props}></Icon>
