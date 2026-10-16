<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01dflzvf.css';
import '../../css/g/go95lyb-o.css';
import '../../css/d/dsc4racke.css';
import '../../css/q/qdq7cabwt.css';
import '../../css/l/leh-9ubya.css';
import '../../css/z/zmd7ce43y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="go95lyb-o"/><path class="dsc4racke"/><path class="qdq7cabwt"/><path class="leh-9ubya"/><path class="zmd7ce43y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-box-plot-20-bold" {...props}></Icon>
