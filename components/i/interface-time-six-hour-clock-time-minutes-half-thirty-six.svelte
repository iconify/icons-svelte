<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhd5bpl-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yhd5bpl-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-six-hour-clock-time-minutes-half-thirty-six" {...props}></Icon>
