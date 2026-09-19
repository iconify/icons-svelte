<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu4msfb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu4msfb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-camera-movie" {...props}></Icon>
