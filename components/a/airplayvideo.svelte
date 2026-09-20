<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbhz3rbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbhz3rbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:airplayvideo" {...props}></Icon>
