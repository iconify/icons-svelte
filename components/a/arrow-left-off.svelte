<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d9q_upw-t.css';
import '../../css/k/kx1edab9u.css';
import '../../css/p/phcgag_tl.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d9q_upw-t"/><path clip-rule="evenodd" class="kx1edab9u"/><path clip-rule="evenodd" class="phcgag_tl"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:arrow-left-off" {...props}></Icon>
