<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2cjbfbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y2cjbfbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-down-outline" {...props}></Icon>
