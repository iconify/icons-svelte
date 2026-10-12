<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x78bggbaj.css';
import '../../css/u/um2797y-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x78bggbaj"/><path class="um2797y-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-scan-filled" {...props}></Icon>
