<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8ybwbcwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w8ybwbcwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:business-hours-sign" {...props}></Icon>
