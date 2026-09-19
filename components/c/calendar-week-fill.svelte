<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm5fokbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rm5fokbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-week-fill" {...props}></Icon>
