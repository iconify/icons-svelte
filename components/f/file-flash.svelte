<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf30wpbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf30wpbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:file-flash" {...props}></Icon>
