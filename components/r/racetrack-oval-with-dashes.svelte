<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q12dtcbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q12dtcbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:racetrack-oval-with-dashes" {...props}></Icon>
