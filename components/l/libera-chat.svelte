<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqo7mbvlt.css';
import '../../css/s/syv4ombst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vqo7mbvlt"/><path class="syv4ombst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libera-chat" {...props}></Icon>
