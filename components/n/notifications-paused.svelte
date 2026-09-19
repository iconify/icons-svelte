<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxcrvh-7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mxcrvh-7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:notifications-paused" {...props}></Icon>
