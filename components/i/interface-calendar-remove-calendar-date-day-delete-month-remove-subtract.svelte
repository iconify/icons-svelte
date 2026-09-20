<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at9917bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="at9917bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-calendar-remove-calendar-date-day-delete-month-remove-subtract" {...props}></Icon>
