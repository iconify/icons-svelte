<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8si1w29y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8si1w29y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:power-outline" {...props}></Icon>
