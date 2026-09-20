<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydtkwuo6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydtkwuo6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:astroluma" {...props}></Icon>
