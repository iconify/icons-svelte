<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spbrxeycp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spbrxeycp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:note-delete" {...props}></Icon>
