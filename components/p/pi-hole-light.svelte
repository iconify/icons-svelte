<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkz8u0d4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkz8u0d4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-hole-light" {...props}></Icon>
