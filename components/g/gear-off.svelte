<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/odcwg15-y.css';
import '../../css/g/gg2r2xahj.css';
import '../../css/c/cdtw6obng.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="odcwg15-y"/><path clip-rule="evenodd" class="gg2r2xahj"/><path clip-rule="evenodd" class="cdtw6obng"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:gear-off" {...props}></Icon>
