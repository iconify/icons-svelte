<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcngc0ydm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcngc0ydm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:earth-fill" {...props}></Icon>
