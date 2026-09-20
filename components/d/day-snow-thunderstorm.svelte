<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig_zqygux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ig_zqygux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-snow-thunderstorm" {...props}></Icon>
