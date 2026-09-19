<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0s_9w4yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0s_9w4yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:comment" {...props}></Icon>
