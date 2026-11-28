<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thowymt8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="thowymt8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-out-thin" {...props}></Icon>
