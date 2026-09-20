<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiyiglb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fiyiglb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:motorcycle-outline" {...props}></Icon>
