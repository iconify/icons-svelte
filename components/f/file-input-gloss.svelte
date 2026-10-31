<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnwnceb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnwnceb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-input-gloss" {...props}></Icon>
