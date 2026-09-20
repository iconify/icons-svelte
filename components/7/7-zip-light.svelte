<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3rg8fb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3rg8fb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:7-zip-light" {...props}></Icon>
