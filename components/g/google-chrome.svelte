<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6qhi552s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6qhi552s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:google-chrome" {...props}></Icon>
