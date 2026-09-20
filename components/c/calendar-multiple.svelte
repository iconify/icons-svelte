<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqiy366ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqiy366ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-multiple" {...props}></Icon>
