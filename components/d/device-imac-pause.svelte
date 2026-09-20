<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by8pelbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by8pelbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-pause" {...props}></Icon>
