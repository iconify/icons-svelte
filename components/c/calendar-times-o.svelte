<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl1alsbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="bl1alsbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:calendar-times-o" {...props}></Icon>
