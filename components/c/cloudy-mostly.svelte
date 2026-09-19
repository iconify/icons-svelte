<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x38mjom2y.css';
import '../../css/t/t_kavccpz.css';
import '../../css/m/ma-vyac-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x38mjom2y"/><path class="t_kavccpz"/><path class="ma-vyac-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:cloudy-mostly" {...props}></Icon>
