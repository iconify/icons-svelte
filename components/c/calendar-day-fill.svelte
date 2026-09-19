<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glq9k8b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="glq9k8b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-day-fill" {...props}></Icon>
