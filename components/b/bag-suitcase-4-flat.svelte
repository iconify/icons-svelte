<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p71m-ys5l.css';
import '../../css/z/zjq1ew06h.css';
import '../../css/o/of-4y9qcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p71m-ys5l"/><path class="zjq1ew06h"/><path class="of-4y9qcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:bag-suitcase-4-flat" {...props}></Icon>
