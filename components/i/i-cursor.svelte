<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wufx3cn9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="wufx3cn9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:i-cursor" {...props}></Icon>
