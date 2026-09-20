<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h29tk6bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h29tk6bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-calendar-blank-calendar-date-day-month" {...props}></Icon>
