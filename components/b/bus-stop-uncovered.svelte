<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytdaeym0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytdaeym0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-stop-uncovered" {...props}></Icon>
