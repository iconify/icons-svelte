<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxj_-80zx.css';
import '../../css/p/pkq5p1b7q.css';
import '../../css/t/t3bhb6x7o.css';
import '../../css/b/byle89bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mxj_-80zx"/><path class="pkq5p1b7q"/><path class="t3bhb6x7o"/><path class="byle89bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:greenhouse-effect-20" {...props}></Icon>
