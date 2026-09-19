<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_v23dcth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_v23dcth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-event-fill" {...props}></Icon>
