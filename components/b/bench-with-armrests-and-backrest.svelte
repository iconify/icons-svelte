<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnzmslbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dnzmslbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bench-with-armrests-and-backrest" {...props}></Icon>
