<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e46-h6c3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e46-h6c3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:move" {...props}></Icon>
