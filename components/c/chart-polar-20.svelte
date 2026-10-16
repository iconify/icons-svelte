<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t__qwuc_d.css';
import '../../css/l/lrulo-bxw.css';
import '../../css/u/uak1w0bkv.css';
import '../../css/o/o93ggxb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t__qwuc_d"/><path class="lrulo-bxw"/><path class="uak1w0bkv"/><path class="o93ggxb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-polar-20" {...props}></Icon>
