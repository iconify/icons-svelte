<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf6_mjbtg.css';
import '../../css/r/rpy7blvsf.css';
import '../../css/y/yc61-tb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gf6_mjbtg"/><path class="rpy7blvsf"/><path class="yc61-tb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:police-station-48-bold" {...props}></Icon>
