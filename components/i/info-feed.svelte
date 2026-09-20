<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1p0z0bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e1p0z0bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:info-feed" {...props}></Icon>
