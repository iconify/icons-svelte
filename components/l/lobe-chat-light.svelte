<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an4-ohbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an4-ohbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lobe-chat-light" {...props}></Icon>
