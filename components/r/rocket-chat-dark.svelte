<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pidtgwfoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pidtgwfoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rocket-chat-dark" {...props}></Icon>
