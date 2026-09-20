<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guyv63blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="guyv63blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-stop-watch-quarter-time-fifteen-quarter-stopwatch-minute-measure-seconds" {...props}></Icon>
