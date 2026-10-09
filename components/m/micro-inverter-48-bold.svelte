<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c876zybxx.css';
import '../../css/n/njny6bb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c876zybxx"/><path class="njny6bb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-inverter-48-bold" {...props}></Icon>
