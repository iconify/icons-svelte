<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ci5117w1h.css';
import '../../css/a/a47_f0m3e.css';
import '../../css/p/p_j979b9g.css';
import '../../css/e/enbo6ebuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ci5117w1h"/><path class="a47_f0m3e"/><path class="p_j979b9g"/><path class="enbo6ebuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:compass-outline" {...props}></Icon>
