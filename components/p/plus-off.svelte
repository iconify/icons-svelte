<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y2rh6zbsu.css';
import '../../css/m/m2m32f12q.css';
import '../../css/r/r9ldy4ixa.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y2rh6zbsu"/><path class="m2m32f12q"/><path class="r9ldy4ixa"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:plus-off" {...props}></Icon>
