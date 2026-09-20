<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcgo1w6kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lcgo1w6kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-strands-dark" {...props}></Icon>
