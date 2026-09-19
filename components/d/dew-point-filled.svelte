<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th7ll35oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="th7ll35oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dew-point-filled" {...props}></Icon>
