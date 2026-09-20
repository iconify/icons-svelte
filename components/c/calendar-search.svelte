<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo_914b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo_914b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-search" {...props}></Icon>
