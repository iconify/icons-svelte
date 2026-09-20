<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoq3slb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="uoq3slb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waxing-gibbous-2" {...props}></Icon>
