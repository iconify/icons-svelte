<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgk77_x6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgk77_x6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bug-play-line" {...props}></Icon>
