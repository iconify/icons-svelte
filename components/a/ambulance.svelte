<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bnrk32e2w.css';
import '../../css/u/u6kjrrbff.css';
import '../../css/b/bxv5zqbfw.css';
import '../../css/p/pgkotf3_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><g transform="translate(2 2)"><circle class="bnrk32e2w"/><ellipse class="u6kjrrbff"/><path class="bxv5zqbfw"/></g><path class="pgkotf3_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:ambulance" {...props}></Icon>
