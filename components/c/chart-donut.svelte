<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/ts5anevge.css';
import '../../css/r/r0eias71k.css';
import '../../css/w/wqthkk89l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":88,"height":88};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ts5anevge"/><path class="r0eias71k"/><path class="wqthkk89l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:chart-donut" {...props}></Icon>
