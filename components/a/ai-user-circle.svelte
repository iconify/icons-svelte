<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ps16brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3ps16brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ai-user-circle" {...props}></Icon>
