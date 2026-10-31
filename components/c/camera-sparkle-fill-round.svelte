<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyp6oz34c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyp6oz34c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-sparkle-fill-round" {...props}></Icon>
