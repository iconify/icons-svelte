<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiecv_t_z.css';
import '../../css/w/wryrt8b-k.css';
import '../../css/f/f5yzw-ygz.css';
import '../../css/u/ulazcvbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aiecv_t_z"/><path class="wryrt8b-k"/><path class="f5yzw-ygz"/><path class="ulazcvbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ambulance-48-bold" {...props}></Icon>
