<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1erivbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h1erivbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-stop-watch-half-quarter-seconds-thirty-hour-half-measure-time-stopwatch" {...props}></Icon>
