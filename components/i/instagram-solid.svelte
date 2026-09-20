<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnh_3dhgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnh_3dhgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:instagram-solid" {...props}></Icon>
