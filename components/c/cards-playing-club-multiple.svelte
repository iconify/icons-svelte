<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty8jpl51r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty8jpl51r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-club-multiple" {...props}></Icon>
