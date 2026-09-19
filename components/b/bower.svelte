<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/h/h3h8vqtwk.css';
import '../../css/m/mtpu2lbjs.css';
import '../../css/d/dijf3d1vx.css';
import '../../css/e/ec_958bcv.css';
import '../../css/t/t1feu8b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="h3h8vqtwk"/><path class="mtpu2lbjs"/><path class="dijf3d1vx"/><path class="ec_958bcv"/><path class="t1feu8b3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:bower" {...props}></Icon>
