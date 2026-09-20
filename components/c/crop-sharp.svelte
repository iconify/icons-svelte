<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szyg5_byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szyg5_byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:crop-sharp" {...props}></Icon>
