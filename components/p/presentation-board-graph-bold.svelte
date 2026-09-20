<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt680ud3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt680ud3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:presentation-board-graph-bold" {...props}></Icon>
