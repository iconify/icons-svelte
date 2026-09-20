<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rptwl7fjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rptwl7fjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-gemini-dark" {...props}></Icon>
