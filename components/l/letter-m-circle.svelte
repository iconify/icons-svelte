<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeioc8poi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeioc8poi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-m-circle" {...props}></Icon>
