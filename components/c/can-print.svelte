<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ewxr_5mgv.css';
import '../../css/v/v7k1qo54j.css';
import '../../css/d/dgb86uv6c.css';
import '../../css/o/o8rtmh1bo.css';
import '../../css/h/h972qfbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ewxr_5mgv"/><path clip-rule="evenodd" class="v7k1qo54j"/><path clip-rule="evenodd" class="dgb86uv6c"/><path class="o8rtmh1bo"/><path class="h972qfbbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:can-print" {...props}></Icon>
