<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3zawtbgl.css';
import '../../css/v/vvsj8nuvg.css';
import '../../css/c/cg6-adcsl.css';
import '../../css/z/zzce84blf.css';
import '../../css/v/vjpczricd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m3zawtbgl"/><path class="vvsj8nuvg"/><path class="cg6-adcsl"/><path class="zzce84blf"/><path class="vjpczricd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ch4-molecule-20-bold" {...props}></Icon>
