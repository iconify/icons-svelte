<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p270hkbyv.css';
import '../../css/l/l9etfhdic.css';
import '../../css/r/r1ehujbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p270hkbyv"/><path class="l9etfhdic"/><path class="r1ehujbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-mount-48" {...props}></Icon>
