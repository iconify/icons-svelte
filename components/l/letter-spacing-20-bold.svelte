<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdbuaia-f.css';
import '../../css/h/hl_idtb9j.css';
import '../../css/l/l2_7mneno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xdbuaia-f"/><path class="hl_idtb9j"/><path class="l2_7mneno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-spacing-20-bold" {...props}></Icon>
