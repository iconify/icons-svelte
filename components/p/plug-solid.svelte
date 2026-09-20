<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5gsjlbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5gsjlbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:plug-solid" {...props}></Icon>
