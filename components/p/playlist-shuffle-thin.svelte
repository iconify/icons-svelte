<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if4ef9-sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if4ef9-sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-shuffle-thin" {...props}></Icon>
