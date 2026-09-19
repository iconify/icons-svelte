<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi3u4bkjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi3u4bkjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:recycle-03" {...props}></Icon>
