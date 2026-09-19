<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk-tdu_gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zk-tdu_gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-left-16-solid" {...props}></Icon>
