<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7wb0ibza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7wb0ibza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-physical-web" {...props}></Icon>
