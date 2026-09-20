<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbc358yre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bbc358yre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-calendar-disable-calendar-date-day-delete-disable-month-remove" {...props}></Icon>
