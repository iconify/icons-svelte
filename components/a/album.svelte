<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/t1edgcb6p.css';
import '../../css/l/lw2u413yi.css';
import '../../css/d/ds3o1_brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="t1edgcb6p"/><path class="lw2u413yi"/><path class="ds3o1_brx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:album" {...props}></Icon>
