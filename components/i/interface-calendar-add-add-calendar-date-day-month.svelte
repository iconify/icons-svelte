<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucwmz4b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ucwmz4b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-calendar-add-add-calendar-date-day-month" {...props}></Icon>
