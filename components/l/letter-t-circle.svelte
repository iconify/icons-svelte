<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1x3n41vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1x3n41vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-t-circle" {...props}></Icon>
