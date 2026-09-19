<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_bmfccdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q_bmfccdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-x-fill" {...props}></Icon>
