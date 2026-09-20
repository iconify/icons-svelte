<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoy0pabhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xoy0pabhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-voice-dark" {...props}></Icon>
