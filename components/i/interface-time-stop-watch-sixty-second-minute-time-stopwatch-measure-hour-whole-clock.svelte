<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkuni3b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xkuni3b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-stop-watch-sixty-second-minute-time-stopwatch-measure-hour-whole-clock" {...props}></Icon>
