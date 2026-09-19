<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lr8euubyt.css';
import '../../css/y/ykg6whbsy.css';
import '../../css/r/retufz7fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":88,"height":88};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lr8euubyt"/><path class="ykg6whbsy"/><path class="retufz7fu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:chart-pie" {...props}></Icon>
