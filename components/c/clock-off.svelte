<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zy93ic7yd.css';
import '../../css/m/mhdxriite.css';
import '../../css/h/hjiy5kq8c.css';
import '../../css/e/ektp6ob5f.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="zy93ic7yd"/><path clip-rule="evenodd" class="mhdxriite"/><path clip-rule="evenodd" class="hjiy5kq8c"/><path clip-rule="evenodd" class="ektp6ob5f"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:clock-off" {...props}></Icon>
