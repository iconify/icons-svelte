<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi_1hp_-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_1hp_-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:party-popper" {...props}></Icon>
