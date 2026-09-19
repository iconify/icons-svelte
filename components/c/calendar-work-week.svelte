<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8f4job8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p8f4job8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:calendar-work-week" {...props}></Icon>
