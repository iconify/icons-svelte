<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a25b49but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a25b49but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-nearby" {...props}></Icon>
