<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxmqlcbnm.css';
import '../../css/o/ot0n8509i.css';
import '../../css/v/vof4c6k-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fxmqlcbnm"/><path class="ot0n8509i"/><path class="vof4c6k-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:motion-sensor-20" {...props}></Icon>
