<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy7ehdcff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy7ehdcff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-plus" {...props}></Icon>
