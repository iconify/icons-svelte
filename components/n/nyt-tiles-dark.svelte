<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3vlycc2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3vlycc2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-tiles-dark" {...props}></Icon>
