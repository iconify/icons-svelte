<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hea10li5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hea10li5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:line-dash-dot-dot" {...props}></Icon>
