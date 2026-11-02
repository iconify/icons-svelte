<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ublamsqky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ublamsqky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-play-line" {...props}></Icon>
