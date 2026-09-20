<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/u/u8xmwksak.css';
import '../../css/p/p-wxpmsdv.css';
import '../../css/w/w1cu-249y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="u8xmwksak"/><path class="p-wxpmsdv"/><path class="w1cu-249y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:clipboard-copy" {...props}></Icon>
