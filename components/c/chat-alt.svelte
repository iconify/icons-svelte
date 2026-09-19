<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdmzamy-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":512};
const content = `<path class="qdmzamy-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:chat-alt" {...props}></Icon>
