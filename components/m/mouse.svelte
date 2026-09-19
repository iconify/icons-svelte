<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie0u-y0-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="ie0u-y0-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mouse" {...props}></Icon>
