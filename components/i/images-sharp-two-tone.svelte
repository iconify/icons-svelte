<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xtbju33sf.css';
import '../../css/g/gzuovjbor.css';
import '../../css/y/y-gfmr48b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xtbju33sf"/><path class="gzuovjbor"/><path class="y-gfmr48b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:images-sharp-two-tone" {...props}></Icon>
