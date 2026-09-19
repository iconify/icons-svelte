<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/s/s963lnjyn.css';
import '../../css/r/raeld23bm.css';
import '../../css/b/bmnwrrbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s963lnjyn"/><path class="raeld23bm"/><path class="bmnwrrbsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:radish" {...props}></Icon>
