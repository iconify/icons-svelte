<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jko8f0oqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="jko8f0oqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-21" {...props}></Icon>
