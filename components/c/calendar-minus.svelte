<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs8i7or4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs8i7or4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-minus" {...props}></Icon>
