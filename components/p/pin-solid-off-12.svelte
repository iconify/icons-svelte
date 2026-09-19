<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yflbjybba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yflbjybba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pin-solid-off-12" {...props}></Icon>
