<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lazrhbojf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="lazrhbojf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:quote-left" {...props}></Icon>
