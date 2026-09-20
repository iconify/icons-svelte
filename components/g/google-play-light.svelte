<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aymxbjbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aymxbjbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-play-light" {...props}></Icon>
