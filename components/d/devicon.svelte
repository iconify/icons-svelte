<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_e3jkbdy.css';
import '../../css/v/vwi7rfg8q.css';
import '../../css/z/zb-92zz6n.css';
import '../../css/p/p-zibkb0b.css';
import '../../css/e/e8wdsnbcv.css';
import '../../css/o/ont3nvb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b_e3jkbdy"/><path class="vwi7rfg8q"/><path class="zb-92zz6n"/><path class="p-zibkb0b"/><path class="e8wdsnbcv"/><path class="ont3nvb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:devicon" {...props}></Icon>
