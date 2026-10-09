<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqlp_3l8j.css';
import '../../css/x/xajndacdt.css';
import '../../css/t/tco_xthkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqlp_3l8j"/><path class="xajndacdt"/><path class="tco_xthkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:log-out-48" {...props}></Icon>
