<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsh9rtrrg.css';
import '../../css/p/pnm561ulh.css';
import '../../css/r/r10cmbc9l.css';
import '../../css/g/gyw-nbbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="tsh9rtrrg"><rect class="pnm561ulh"/><rect class="r10cmbc9l"/><rect class="gyw-nbbys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:columns-3-bold" {...props}></Icon>
