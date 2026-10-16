<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_q7i3b9l.css';
import '../../css/h/hw_xbachc.css';
import '../../css/c/chbbpgb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h_q7i3b9l"/><path class="hw_xbachc"/><path class="chbbpgb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-ship-48-bold" {...props}></Icon>
