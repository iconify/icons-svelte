<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3--6bbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j3--6bbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:delta-chat-dark" {...props}></Icon>
