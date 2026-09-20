<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7bk3rb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c7bk3rb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-time-clock-nine-to-five-work-hour-time-clock" {...props}></Icon>
