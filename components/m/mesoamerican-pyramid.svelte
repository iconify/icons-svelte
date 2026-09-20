<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggy21bbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ggy21bbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mesoamerican-pyramid" {...props}></Icon>
