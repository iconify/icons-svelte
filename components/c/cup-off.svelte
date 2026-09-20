<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dvdb5bc0m.css';
import '../../css/f/fiddvovtr.css';
import '../../css/v/vy59pubxe.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="dvdb5bc0m"/><path clip-rule="evenodd" class="fiddvovtr"/><path class="vy59pubxe"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:cup-off" {...props}></Icon>
