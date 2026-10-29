<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fci6hf7ny.css';
import '../../css/m/mhdr543mh.css';
import '../../css/e/e18g5nbpy.css';
import '../../css/v/vgssyxiqi.css';
import '../../css/e/e166uhm4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fci6hf7ny wm-deco"/><path class="mhdr543mh wm-deco"/><path class="e18g5nbpy wm-k"/><path class="vgssyxiqi wm-a"/><path class="e166uhm4q wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:indent-increase-blueprint" {...props}></Icon>
