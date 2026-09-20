<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elril8byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elril8byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nrk-tv-light" {...props}></Icon>
