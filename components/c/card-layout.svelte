<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt9muxegx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt9muxegx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:card-layout" {...props}></Icon>
