<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkthjaced.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkthjaced"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevrons-vertical-2" {...props}></Icon>
