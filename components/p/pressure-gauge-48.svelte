<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhk2u_byh.css';
import '../../css/l/l6j-txiai.css';
import '../../css/w/w6sns4blb.css';
import '../../css/b/bht8vx5nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zhk2u_byh"/><path class="l6j-txiai"/><path class="w6sns4blb"/><path class="bht8vx5nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pressure-gauge-48" {...props}></Icon>
