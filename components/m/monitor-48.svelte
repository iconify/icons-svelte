<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xszfmab4u.css';
import '../../css/e/ezx2ctbsk.css';
import '../../css/n/nh3pp-bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xszfmab4u"/><path class="ezx2ctbsk"/><path class="nh3pp-bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-48" {...props}></Icon>
