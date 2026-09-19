<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh4hakjtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gh4hakjtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:eraser" {...props}></Icon>
