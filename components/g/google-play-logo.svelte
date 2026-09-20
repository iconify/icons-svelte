<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg36jbbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg36jbbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-play-logo" {...props}></Icon>
