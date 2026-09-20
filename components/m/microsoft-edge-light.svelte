<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni_93gbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni_93gbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-edge-light" {...props}></Icon>
