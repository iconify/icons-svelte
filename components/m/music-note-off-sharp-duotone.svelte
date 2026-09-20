<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zcsjmmbtn.css';
import '../../css/r/rn72_7b7r.css';
import '../../css/f/f4vx4ccga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zcsjmmbtn"/><path class="rn72_7b7r"/><path class="f4vx4ccga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:music-note-off-sharp-duotone" {...props}></Icon>
