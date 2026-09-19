<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpwh6abex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zpwh6abex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:google-play" {...props}></Icon>
