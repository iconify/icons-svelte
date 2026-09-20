<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukznrbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vukznrbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cross-bolnisi" {...props}></Icon>
