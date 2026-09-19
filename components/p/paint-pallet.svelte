<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eomg5oe0j.css';
import '../../css/n/njcmzh3nb.css';
import '../../css/g/gg5y9t4ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eomg5oe0j"/><path class="njcmzh3nb"/><path clip-rule="evenodd" class="gg5y9t4ah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:paint-pallet" {...props}></Icon>
