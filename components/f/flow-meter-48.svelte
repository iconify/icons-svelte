<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5e3kibxu.css';
import '../../css/d/d2h5byb5d.css';
import '../../css/p/pqlptybrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5e3kibxu"/><path class="d2h5byb5d"/><path class="pqlptybrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-meter-48" {...props}></Icon>
