<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gag497ble.css';
import '../../css/e/e0fv-pquy.css';
import '../../css/y/yt-6yebqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="gag497ble"/><path clip-rule="evenodd" class="e0fv-pquy"/><path class="yt-6yebqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:color-picker-print" {...props}></Icon>
