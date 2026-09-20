<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1gv_2ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1gv_2ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bluesky" {...props}></Icon>
