<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmghfvc3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rmghfvc3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-ww" {...props}></Icon>
