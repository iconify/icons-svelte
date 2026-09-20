<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1b1a9bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1b1a9bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-socket-canada" {...props}></Icon>
