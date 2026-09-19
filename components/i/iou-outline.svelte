<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/haqszuawp.css';
import '../../css/n/n289_rbfx.css';
import '../../css/m/mhcrz7bok.css';
import '../../css/i/i6ykxkjyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="haqszuawp"/><rect class="n289_rbfx"/><path class="mhcrz7bok"/><path class="i6ykxkjyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:iou-outline" {...props}></Icon>
