<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkk820mfz.css';
import '../../css/w/w2_kf1b2m.css';
import '../../css/y/yk26dnbcq.css';
import '../../css/y/ywwm5s49b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hkk820mfz"/><path class="w2_kf1b2m"/><path class="yk26dnbcq"/><path class="ywwm5s49b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:autonomous-car-48" {...props}></Icon>
