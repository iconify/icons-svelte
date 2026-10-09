<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meve8lt-m.css';
import '../../css/l/l4lrodbjn.css';
import '../../css/y/ywo35nt_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="meve8lt-m"/><path class="l4lrodbjn"/><path class="ywo35nt_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-tent-48" {...props}></Icon>
