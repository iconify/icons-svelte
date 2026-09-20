<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdl3dgbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdl3dgbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkerboard-remove" {...props}></Icon>
