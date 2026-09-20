<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_61xr4wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j_61xr4wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dog" {...props}></Icon>
