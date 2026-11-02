<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n43lisbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n43lisbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-edit-line" {...props}></Icon>
