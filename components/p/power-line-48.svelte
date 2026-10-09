<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbo4sbc_y.css';
import '../../css/o/oowff5lqf.css';
import '../../css/q/qs2b_84ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mbo4sbc_y"/><path class="oowff5lqf"/><path class="qs2b_84ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-line-48" {...props}></Icon>
