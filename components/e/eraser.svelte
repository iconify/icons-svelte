<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv_tqlb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rv_tqlb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:eraser" {...props}></Icon>
