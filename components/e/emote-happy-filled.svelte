<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-ctd02e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="iq-ctd02e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:emote-happy-filled" {...props}></Icon>
