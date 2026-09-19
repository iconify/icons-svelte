<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j8wxn8xap.css';
import '../../css/g/g5q9qkbwi.css';
import '../../css/x/x3_kr2bze.css';
import '../../css/v/vl_70lije.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="j8wxn8xap"/><path clip-rule="evenodd" class="g5q9qkbwi"/><path clip-rule="evenodd" class="x3_kr2bze"/><path class="vl_70lije"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result-invalid2x-outline" {...props}></Icon>
