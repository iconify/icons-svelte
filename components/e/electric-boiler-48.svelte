<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h43e48bgp.css';
import '../../css/r/r8v8d6bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h43e48bgp"/><path class="r8v8d6bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-boiler-48" {...props}></Icon>
