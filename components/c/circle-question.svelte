<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km-r1bbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km-r1bbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:circle-question" {...props}></Icon>
