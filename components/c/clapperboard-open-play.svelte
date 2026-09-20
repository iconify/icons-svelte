<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd1zls1cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd1zls1cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clapperboard-open-play" {...props}></Icon>
