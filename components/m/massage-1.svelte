<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm9xzf3xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dm9xzf3xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:massage-1" {...props}></Icon>
