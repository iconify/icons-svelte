<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuy3je-si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuy3je-si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-space-between-sharp" {...props}></Icon>
