<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdl857bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdl857bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:checks-line" {...props}></Icon>
