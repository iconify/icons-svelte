<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swbrv-bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swbrv-bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-multiple-check" {...props}></Icon>
