<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnq8kx7dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="rnq8kx7dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-sleet" {...props}></Icon>
