<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eodp9ed2n.css';
import '../../css/r/rfdis-bgk.css';
import '../../css/p/pc88fcihq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eodp9ed2n"/><path class="rfdis-bgk"/><path class="pc88fcihq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:joystick-48" {...props}></Icon>
