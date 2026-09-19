<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf1u95bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nf1u95bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-left-ellipsis-16-solid" {...props}></Icon>
