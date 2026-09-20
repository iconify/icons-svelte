<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-r3bw6mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-r3bw6mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mosque" {...props}></Icon>
