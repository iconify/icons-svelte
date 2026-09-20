<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b67elxamo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b67elxamo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mp4-document" {...props}></Icon>
