<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l68l_w4ab.css';
import '../../css/u/u8ql_i1-b.css';
import '../../css/m/mc4-2c-lz.css';
import '../../css/b/bvoz1whzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="l68l_w4ab"/><path clip-rule="evenodd" class="u8ql_i1-b"/><path class="mc4-2c-lz"/><path clip-rule="evenodd" class="bvoz1whzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:percent-outline" {...props}></Icon>
