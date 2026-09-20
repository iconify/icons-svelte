<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvoaqteur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xvoaqteur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-pin-with-dot-above-outstretched-hand" {...props}></Icon>
