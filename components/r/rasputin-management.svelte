<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivd6g4r7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivd6g4r7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rasputin-management" {...props}></Icon>
