<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i69ysub0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i69ysub0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fedex-light" {...props}></Icon>
