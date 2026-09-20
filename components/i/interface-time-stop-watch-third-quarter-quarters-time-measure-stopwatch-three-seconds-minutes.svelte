<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsm5h63ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xsm5h63ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-stop-watch-third-quarter-quarters-time-measure-stopwatch-three-seconds-minutes" {...props}></Icon>
