<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jd8hznqdc.css';
import '../../css/z/zs5_5_csw.css';
import '../../css/m/mud-36bku.css';
import '../../css/b/b--zx2sbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jd8hznqdc"/><rect class="zs5_5_csw"/><path clip-rule="evenodd" class="mud-36bku"/><path class="b--zx2sbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:images" {...props}></Icon>
