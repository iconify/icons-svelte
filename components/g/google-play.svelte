<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5vwuc8im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v5vwuc8im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:google-play" {...props}></Icon>
