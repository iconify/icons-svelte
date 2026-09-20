<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmh8azp6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmh8azp6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-down-box-sharp" {...props}></Icon>
