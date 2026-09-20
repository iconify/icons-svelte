<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb5navbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sb5navbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:move-layer-up" {...props}></Icon>
