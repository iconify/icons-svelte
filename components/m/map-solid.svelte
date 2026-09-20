<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0pn9dbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0pn9dbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:map-solid" {...props}></Icon>
