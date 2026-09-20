<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6f4sq5sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6f4sq5sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rocket-chat" {...props}></Icon>
