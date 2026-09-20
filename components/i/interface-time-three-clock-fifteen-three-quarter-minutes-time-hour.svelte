<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7p48actu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m7p48actu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-three-clock-fifteen-three-quarter-minutes-time-hour" {...props}></Icon>
