<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_5_8kbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r_5_8kbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reopen-pages" {...props}></Icon>
