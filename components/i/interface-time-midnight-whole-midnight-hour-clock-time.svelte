<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xukn4qufr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xukn4qufr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-midnight-whole-midnight-hour-clock-time" {...props}></Icon>
