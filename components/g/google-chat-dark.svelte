<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xul7zyimb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xul7zyimb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-chat-dark" {...props}></Icon>
