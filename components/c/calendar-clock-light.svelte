<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqqnc8b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tqqnc8b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-clock-light" {...props}></Icon>
