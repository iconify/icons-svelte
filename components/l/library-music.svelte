<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgup0bcsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgup0bcsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:library-music" {...props}></Icon>
