<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkluasbjw.css';
import '../../css/m/moudosbgx.css';
import '../../css/o/olb-5xpso.css';
import '../../css/f/f-9u6xbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkluasbjw"/><path class="moudosbgx"/><path class="olb-5xpso"/><path class="f-9u6xbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ceiling-fan-20-bold" {...props}></Icon>
