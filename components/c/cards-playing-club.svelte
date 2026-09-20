<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r472rcckr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r472rcckr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-club" {...props}></Icon>
