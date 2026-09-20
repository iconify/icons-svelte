<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rss44_aio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rss44_aio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar3-filled" {...props}></Icon>
