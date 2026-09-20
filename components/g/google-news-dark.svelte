<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruxc2r0ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ruxc2r0ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-news-dark" {...props}></Icon>
