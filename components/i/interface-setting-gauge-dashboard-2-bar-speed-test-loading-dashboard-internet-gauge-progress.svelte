<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5fnum5ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="t5fnum5ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-setting-gauge-dashboard-2-bar-speed-test-loading-dashboard-internet-gauge-progress" {...props}></Icon>
