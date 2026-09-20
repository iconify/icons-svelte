<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-4c9b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="to-4c9b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:calendar-with-wheelie-bin" {...props}></Icon>
