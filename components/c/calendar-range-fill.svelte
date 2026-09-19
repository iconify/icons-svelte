<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abeen-81d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="abeen-81d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-range-fill" {...props}></Icon>
