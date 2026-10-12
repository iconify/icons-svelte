<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1625qbk.css';
import '../../css/v/v0h99ub0p.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vq1625qbk"/><path class="v0h99ub0p"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clock-plus-48-bold" {...props}></Icon>
