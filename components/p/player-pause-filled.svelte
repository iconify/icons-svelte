<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e06y5c2ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e06y5c2ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-pause-filled" {...props}></Icon>
